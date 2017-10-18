# Toggle Button Twitter Style
A style for `ToggleButton` control to make them look like Twitter's Like Button.

## Preview
![Image Preview](ToggleButtonTwitterStyle.gif "Image Preview")

## Usage
There are 3 Styles available:
* `ToggleButtonHeartStyle`
* `ToggleButtonSmileyStyle`
* `ToggleButtonStarStyle`

Use the ones you require. To use it for your own icon:
* Get the `ToggleButtonHeartStyle`
* Change the `Glyph` in the `Icon`
* Change the Red color to your required colour in all the places
* Change the Yellow color in `MainTransition` to a complementary colour
* You are good to go!

Checked with **Windows 10 Creators Update 15063**

### Inspired from
* [Twitter's like animation in Android - alternative](http://frogermcs.github.io/twitters-like-animation-in-android-alternative/)
* [jd-alexander/LikeButton](https://github.com/jd-alexander/LikeButton)

### Known Issues
* Not tested with touch. Might require adding few other transitions.
* Doesn't work if the pointer is moved fast after clicking (It changes state too fast)