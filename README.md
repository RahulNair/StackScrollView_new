StackScrollView for android
===================
                                        Twitter Like StackScrollView In Android


This StackScrollView is already available for iPad on GitHub, This was created by the mobile development team at raw engineering. Now here’s the android version of the same, from raw engineering.

Getting Started
StackScrollView is comprised of four classes, RootViewController,MenuViewFragment and StackScrollView and DataViewFragment .

Role of the above classes is as under :-
-RootViewContoller , This is a launcher class in which we add the StackScrollView.Initially we have a parent root which is a FrameLayout , in that we add two child view namely LeftView and RightView.

-The LeftView contains MenuViewFragment Which extends ListFragments, and on RightView we add instance of StackScrollView which extends FrameLayout.

-Now on click of any item in the MenuViewFragment , a new object of DataViewFragment,(which extends ListFragment) is created.

-Then instance of DataViewFragment is added into the StackScrollView's instance that we had created in RootViewController class.

-Now on click of any item in DataViewFragment, we add a new object of DataviewFragment to StackScollView.
