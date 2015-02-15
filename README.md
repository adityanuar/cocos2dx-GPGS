# cocos2dx-GPGS
Google Play Service library to work with Cocos2d-x Framework

This module was derived from the work from carlospinan (https://github.com/cpinan/Cocos2dX_GooglePlayGamesServices.git) and howlryu (https://github.com/howlryu/Cocos2dX3.2_GooglePlayGamesServices.git) with additional leaderboard & analytic functions. Thanks for the great works :)

It includes several methods so far from google play service such as:

isSignedIn();
signIn();
signOut();
========= Leaderboard =================
submitScore(const char* leaderboardID, long score);
showLeaderboards();
showLeaderboard(const char* leaderboardID);
loadScoreOfLeaderBoard(const char* leaderboardID);
getRawScore();
========= Achievements ================
unlockAchievement(const char* achievementID);
incrementAchievement(const char* achievementID, int numSteps);
showAchievements();
========= Analytic ====================
setScreenName(const char* name);
setEvent(const char* categoryId, const char* actionId, const char* labelId);
========= Admob =======================
initAd();
showAd();
hideAd();
preloadInterstitialAd();
showInterstitialAd();

Just merge necessary codes in this modules on your projects to use it.

Facebook and google iap billing are planned to be added in the future. Any contributions are welcome :)