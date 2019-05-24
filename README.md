# HandProprioceptiveTrainingApp

This is a project to build an app that would test Hand Proprioception

## V0
1. Built a basic template of the hand proprioceptive training app
2. .kv and .py file separately filed
3. Colors were randomly picked from a set of choices
4. Everything in one FloatLayout

## V1
1. Basic adaptive staircase algorithm applied(introduced in Block et al., 2019)
2. .kv and .py merged into one .py file
3. Colors are now chosen from the set of three pairs (Red/Blue, Yellow/Purple, Green/Pink)
4. RelativeLayout is used to incorporate different items
5. ScreenManager is used to move from one screen to the other
6. Gridlines are prepared for the initial calibration

## V1 (update: 19.05.08)
1. A screen that gets user input has been created
  - Participant ID
  - Initial degree change
  - Hand Dominance
  - Finger width
  - Finger length
2. Based on the user input, the color screen will be generated and operated

## V1 (update: 19.05.23)
1. Two parameter input screens
  1) Screen 1
    - Participant ID
    - Age
    - Gender
    - Hand Dominance
   2) Screen 2
    - Initial step size (degree)
    - Finger length
    - Finger width
    - MP joint radius
* Needs to be done soon
  - The lower border of the test screen should be drawn with respect to the MP joint radius
  
  ~~- The pop-up window to check if calibration is complete~~
  
  ~~- Color randomization -> not to overlap!!~~
* Ideas
  1) Check if a researcher has correctly pushed the next button -> make "Next" doesn't work unless contents saved??
### For V2 (ETA: First week of June)
  1) Experimental data should be saved somewhere
  2) Drop-down menu for different options
    - Mean & SD [Priority]
    - Typical psychophysical function
    - Psi-marginal
  3) The python filename should be "main.py" [Kivy Buildozer requirement]
