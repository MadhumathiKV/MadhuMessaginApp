# MadhuMessaginApp

This is a basic Messaging App used to send and receive messages . 
It shows the inbox messages . 

Libraries used:
 compile fileTree(dir: 'libs', include: ['*.jar'])
    androidTestCompile('com.android.support.test.espresso:espresso-core:2.2.2', {
        exclude group: 'com.android.support', module: 'support-annotations'
    })
    compile 'com.android.support:appcompat-v7:23.4.0'
    compile 'com.android.support.constraint:constraint-layout:1.0.0-alpha5'
    testCompile 'junit:junit:4.12'
