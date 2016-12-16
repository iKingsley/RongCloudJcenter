# SealTalk Powered by RongCloud


# Use

## Step 1 with gradle 

```Java

dependencies {

    compile 'cn.rongcloud.android:IMLib:2.8.3'
    compile 'cn.rongcloud.android:IMKit:2.8.3.1'
    compile 'cn.rongcloud.android:CallLib:2.8.3'
    compile 'cn.rongcloud.android:CallKit:2.8.3.1'

}

```

## Step2 init to Application.java

```Java

RongIM.init(this);

```

## Step3 connect rongcloud server

```Java

RongIM.connect(token)

```

[token](http://www.rongcloud.cn/docs/index.html)

## Step 4 Other

- Use ConversationFragment
- Use ConversationListFragment
- Friends
- Groups

...

[Document](http://www.rongcloud.cn/docs/android.html)


# More

[rongcloud web](rongcloud.cn)

[github -> sealtalk](https://github.com/sealtalk/sealtalk-android)


