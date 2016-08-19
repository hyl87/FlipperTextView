# FlipperTextView
TextView垂直翻页效果


### 效果图

<img src="/1.gif" style="width: 30%;">

#### 使用

 compile 'com.ydw.flippertextview:FlipperTextView:1.0.1'

#### Layout

    <com.ydw.flippertextview.FlipperTextView
        android:id="@+id/flipper"
        android:layout_width="fill_parent"
        android:layout_height="40dip"
        android:layout_centerVertical="true"
        android:layout_marginLeft="10dp"
        android:background="@android:color/white"
        android:gravity="center"/>
#### java
    ArrayList<String> mData =  new ArrayList<String>();
    FlipperTextView mFlipper; mFlipper = ((FlipperTextView) this.findViewById(R.id.flipper));
	mFlipper.setData(mData);
	mFlipper.setFlipInterval(3000);
	mFlipper.startFlipping();
	
####
#####
License

Copyright (C) 2016 401610239@qq.com

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
