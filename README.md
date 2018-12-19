# android-activity-screen-rotation

Method 1:
onSaveInstanceState
onRestoreInstanceState

Method 2:
Different layout for portrait and landscape
res --> layout-land
copy the file from layout and all ids for each components should be same


Method 3:
android manifest --> configChanges --> orientation | screensize
implement onConfigurationChanged