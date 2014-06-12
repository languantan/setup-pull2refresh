Downloading Libraries
============
- "Download Zip" from each of these two libraries and unzip them to Somewhere/
    **https://github.com/chrisbanes/ActionBar-PullToRefresh** 
    **https://github.com/castorflex/SmoothProgressBar**
- You should now have:
1. Somewhere/ActionBar-PullToRefresh/
2. Somewhere/SmoothProgressBar/

Importing Into Eclipse
============
- File > Import... > Android(Existing Android Code...) > Browse...

SmoothProgressBar
----
- Choose **SmoothProgressBar** > *library*
- *New Project Name* > **smoothprogressbar**

ActionBar-PullToRefresh
-----
- Choose **ActionBar-PullToRefresh** > *library*
- *New Project Name* > **pulltorefresh**

Setting Up Dependencies
==========

SmoothProgressBar
----
- Right-click on **smoothprogressbar** project > *Properties*
- From the side bar, *Java Build Path* > *Source* > **Add Folder**
- Select **java**. Click Ok.
- From the side bar again, *Android* > *Target Name* > **Android 4.1.2**
- Under *Library* below, check **Is Library**


ActionBar-PullToRefresh
-----
- Right-click on **pulltorefresh** project > *Properties*
- From the side bar, *Java Build Path* > *Source* > **Add Folder**
- Select **java**. Click Ok.
- From the side bar again, *Android* > *Target Name* > **Android 4.1.2**
- Under *Library* below, check **Is Library**
- Click *Add...*
- Select **smoothprogressbar**.

MunicipalFeedback
-----
- Right-click on **MunicipalFeedback** project > *Properties*
- From the side bar, *Android* > *Target Name*.
- Under *Library* below, Click *Add...*
- Select **pulltorefresh**.
 

