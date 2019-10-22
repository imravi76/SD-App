# SD-App


Android app to perform write, read and delete data from SD Card

Step 1 - Edit the app level build.gradle ![file](app/build.gradle)

implementation 'com.android.support:design:28.0.0'    (For older android sdk versions)

                                        or

implementation 'com.google.android.material:material:1.0.0'       (For Newer AndroidX Version)


Step 2 - Add Write External and Read External permissions to ![AndroidManifest](app/src/main/AndroidManifest.xml) file.



Step 3 - Then, Copy and paste the ![layouts](app/src/main/res/layout/) and ![java code](app/src/main/java/com/example/lab) for both activities.
