# StoneScriptUtils

You can import this script into the Mindstone in Stone Story RPG with the following snippet. Note that this is currently buggy and may not work every time, however if it does load correctly it should be cached for the remainder of the run session of the app. You will need to restart the app to try again. If it does work, comment out the lines in future runs so that it doesn't affect the cache or cause the game to run slow or other issues.

```
var s1=＂https://raw.githubusercontent.com/＂
var s2=＂JoshClark431335/StoneScriptUtils/main/＂
sys.SetFileUrl(string.Format(＂｛0｝｛1｝＂,s1,s2))
```