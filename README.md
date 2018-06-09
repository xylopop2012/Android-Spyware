# Android-Spyware
Could anyone please tell me what this script is actually capable of doing? Its been on my phone for over 2 years.
git remote add origin https://github.com/xylopop2012/Android-Spyware.git
06-08 06:07:56.752 W ReactHockeyApp: RNHockeyApp: Failed to get existing metadata
06-08 06:07:56.752 W ReactHockeyApp: /data/user/0/com.skype.raider/files/HockeyAppCrashMetadata.json (No such file or directory)
06-08 06:07:56.752 W ReactHockeyApp: 	java.io.FileInputStream.open0(FileInputStream.java:-2)
06-08 06:07:56.752 W ReactHockeyApp: 	java.io.FileInputStream.open(FileInputStream.java:200)
06-08 06:07:56.752 W ReactHockeyApp: 	java.io.FileInputStream.<init>(FileInputStream.java:150)
06-08 06:07:56.752 W ReactHockeyApp: 	android.app.ContextImpl.openFileInput(ContextImpl.java:520)
06-08 06:07:56.752 W ReactHockeyApp: 	android.content.ContextWrapper.openFileInput(ContextWrapper.java:200)
06-08 06:07:56.752 W ReactHockeyApp: 	com.skype.hockeyapp.SkypeCrashListener.f(SourceFile:139)
06-08 06:07:56.752 W ReactHockeyApp: 	com.skype.hockeyapp.SkypeCrashListener.<init>(SourceFile:48)
06-08 06:07:56.752 W ReactHockeyApp: 	com.skype.hockeyapp.SkypeCrashListener.a(SourceFile:43)
06-08 06:07:56.752 W ReactHockeyApp: 	com.skype.hockeyapp.SkypeCrashManager.a(SourceFile:37)
06-08 06:07:56.752 W ReactHockeyApp: 	com.skype4life.SkypeApplication.onCreate(SourceFile:1042)
06-08 06:07:56.752 W ReactHockeyApp: 	android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1125)
06-08 06:07:56.752 W ReactHockeyApp: 	android.app.ActivityThread.handleBindApplication(ActivityThread.java:6056)
06-08 06:07:56.752 W ReactHockeyApp: 	android.app.ActivityThread.-wrap1(null:0)
06-08 06:07:56.752 W ReactHockeyApp: 	android.app.ActivityThread$H.handleMessage(ActivityThread.java:1764)
06-08 06:07:56.752 W ReactHockeyApp: 	android.os.Handler.dispatchMessage(Handler.java:105)
06-08 06:07:56.752 W ReactHockeyApp: 	android.os.Looper.loop(Looper.java:164)
06-08 06:07:56.752 W ReactHockeyApp: 	android.app.ActivityThread.main(ActivityThread.java:6938)
06-08 06:07:56.752 W ReactHockeyApp: 	java.lang.reflect.Method.invoke(Method.java:-2)
06-08 06:07:56.752 W ReactHockeyApp: 	com.android.internal.os.Zygote$MethodAndArgsCaller.run(Zygote.java:327)
06-08 06:07:56.752 W ReactHockeyApp: 	com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1374)
06-08 06:07:56.776 I DumpUploader: Preparing check for new crash dumps
06-08 06:07:56.777 I ReactApp: onCreate start
06-08 06:07:56.778 I DumpUploader: Started check for new crash dumps
06-08 06:07:56.779 I DumpUploader: Marking dumps as known: 
06-08 06:07:57.028 I ReactApp: configureViewPools took 0ms
06-08 06:07:57.058 I ReactApp: configureOkHttp took 29ms
06-08 06:07:57.059 I ReactApp: configureStetho took 0ms
06-08 06:07:57.068 I ReactApp: configureYoga took 9ms
06-08 06:07:57.071 I ReactApp: CsiManager.onCreate took 1ms
06-08 06:07:57.160 I ReactApp: mReactNativeHost.getReactInstanceManager took 89ms
06-08 06:07:57.160 I React: Creating react context.
06-08 06:07:57.160 I ReactApp: onCreate complete in 534ms
06-08 06:07:57.162 I PushReceiver: onReceive
06-08 06:07:57.162 I PushHandlingContext: onReceive
06-08 06:07:57.162 I PushHandlingContext: onReceive - no prior WakeLock; starting push handling
06-08 06:07:57.164 I RNBackgroundExecution: startWakefulService(PushHelper), wakelock id: f7820852-8ee9-4a57-9e6b-581ddbd1c2e3, at: 1528438077164
06-08 06:07:57.172 I PushHandlingContext: onReceive - delaying message until PushModule is initialized
06-08 06:07:57.173 I RNBackgroundExecution: completeWakefulIntentAfterAllWakeLocks(PushReceiver), wakelock id: null, at: 1528438077172
06-08 06:07:57.173 I SkypeCameraViewManager: init
06-08 06:07:57.173 I PushHandlingService: Service created
06-08 06:07:57.174 I PushHandlingService: Start push handling. pushId: 1 startId: 1
06-08 06:07:57.175 I UpgradeContext: onReceive action android.intent.action.MY_PACKAGE_REPLACED
06-08 06:07:57.175 I UpgradeContext: acquireWakeLock taskId 1
06-08 06:07:57.179 I UpgradeContext: UpgradeModuleNotReady: task 1, intent pushed to delayedIntentQueue
06-08 06:07:57.180 I SimpleWakefulService: Service created
06-08 06:07:57.181 I SimpleWakefulService: Acquire WAKE_LOCK for taskId: 1 with startId: 1
06-08 06:07:57.193 I GradientImagePackage: createViewManagers
06-08 06:07:57.197 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.ink.AdditiveSurfaceViewManager
06-08 06:07:57.202 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.ink.AdditiveSurfaceViewShadowNode
06-08 06:07:57.210 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.uimanager.h
06-08 06:07:57.216 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.text.g
06-08 06:07:57.227 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.textinput.i
06-08 06:07:57.242 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.art.c
06-08 06:07:57.243 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.art.b
06-08 06:07:57.244 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.art.a
06-08 06:07:57.246 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.progressbar.b
06-08 06:07:57.247 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.text.frescosupport.a
06-08 06:07:57.249 W ViewManagerPropertyUpdater: Could not find generated setter for class com.brentvatne.react.ReactVideoViewManager
06-08 06:07:57.253 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skpcamera.SkypeCameraViewManager
06-08 06:07:57.256 W ViewManagerPropertyUpdater: Could not find generated setter for class com.customkeyboard.CustomKeyboardViewManager
06-08 06:07:57.259 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.slimcore.video.RNCallingVideoViewManager
06-08 06:07:57.262 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.slimcore.video.RNCallingVideoViewLocalManager
06-08 06:07:57.265 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.react.mediapicker.MediaPickerViewManager
06-08 06:07:57.270 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.react.mediapicker.c
06-08 06:07:57.274 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.skypemessagetextinput.view.RNViewManager
06-08 06:07:57.278 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.skypemessagetextinput.view.c
06-08 06:07:57.278 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.reactnativesprites.SpriteViewManager
06-08 06:07:57.281 W ViewManagerPropertyUpdater: Could not find generated setter for class com.projectseptember.RNGL.GLCanvasManager
06-08 06:07:57.284 W ViewManagerPropertyUpdater: Could not find generated setter for class com.github.alinz.reactnativewebviewbridge.WebViewBridgeManager
06-08 06:07:57.290 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapCalloutManager
06-08 06:07:57.293 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapMarkerManager
06-08 06:07:57.298 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapPolylineManager
06-08 06:07:57.300 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapPolygonManager
06-08 06:07:57.303 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapCircleManager
06-08 06:07:57.306 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapManager
06-08 06:07:57.311 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapLiteManager
06-08 06:07:57.312 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapUrlTileManager
06-08 06:07:57.314 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.react.videofxp.VideoFXPViewManager
06-08 06:07:57.316 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.virtualmessageview.VirtualMessageViewControllerManager
06-08 06:07:57.317 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.react.clippedview.ClippedViewManager
06-08 06:07:57.319 W ViewManagerPropertyUpdater: Could not find generated setter for class com.BV.LinearGradient.LinearGradientManager
06-08 06:07:57.321 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.lottie.LottieAnimationViewManager
06-08 06:07:57.324 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.react.gradientimage.GradientImageViewManager
06-08 06:07:57.326 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.qrcode.QRCodeViewManager
06-08 06:07:57.328 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.camera.imagefilter.ImageFilterManager
06-08 06:07:58.991 W JavaModuleHelper: Could not find generated custom module provider
06-08 06:07:58.992 W React: There is no generated module helper for module: AndroidSmsManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.992 W React: There is no generated module helper for module: EnvironmentInfo using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.992 W React: There is no generated module helper for module: SnapshotManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.992 W React: There is no generated module helper for module: RNDocumentPicker using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.992 W React: There is no generated module helper for module: FingerprintingLib using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.992 W React: There is no generated module helper for module: Adjust using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.993 W React: There is no generated module helper for module: RNReload using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.993 W React: There is no generated module helper for module: RNSkypeCredentialsFetcher using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.993 W React: There is no generated module helper for module: AndroidBadges using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.993 W React: There is no generated module helper for module: ExtendedAppState using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.993 W React: There is no generated module helper for module: DeviceSettings using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.993 W React: There is no generated module helper for module: CampaignReceiver using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.994 W React: There is no generated module helper for module: RNNetworkInfo using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.994 W React: There is no generated module helper for module: MediaPicker using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.994 W React: There is no generated module helper for module: DeviceInfo using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.994 W React: There is no generated module helper for module: ZipUtil using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.994 W React: There is no generated module helper for module: RNBackgroundExecution using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.994 W React: There is no generated module helper for module: SoundRecorder using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.994 W React: There is no generated module helper for module: SkypeCamera using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.994 W React: There is no generated module helper for module: SoundPlayer using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.995 W React: There is no generated module helper for module: PlatformConstants using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.995 W React: There is no generated module helper for module: FrescoModule using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.995 W React: There is no generated module helper for module: SplashScreenNotifier using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.995 W React: There is no generated module helper for module: RNCookieManagerAndroid using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.995 W React: There is no generated module helper for module: ExternalBrowser using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.996 W React: There is no generated module helper for module: TimeZoneManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.996 W React: There is no generated module helper for module: ImageResizerAndroid using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.996 W React: There is no generated module helper for module: NativeEntropy using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.996 W React: There is no generated module helper for module: RNCommandInvoker using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.997 W React: There is no generated module helper for module: RNGraphicsContext using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.997 W React: There is no generated module helper for module: StyleTransfer using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.997 W React: There is no generated module helper for module: IncomingCallInteractionManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.997 W React: There is no generated module helper for module: TokenShareModule using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.998 W React: There is no generated module helper for module: CustomKeyboard using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.998 W React: There is no generated module helper for module: ClientLogging using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.998 W React: There is no generated module helper for module: VideoFXP using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.998 W React: There is no generated module helper for module: Contacts using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.998 W React: There is no generated module helper for module: RNStorage using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.998 W React: There is no generated module helper for module: CallMonitor using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.999 W React: There is no generated module helper for module: RNAppUpgrade using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.999 W React: There is no generated module helper for module: RNViewConfig using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.999 W React: There is no generated module helper for module: RNSlimcore using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.999 W React: There is no generated module helper for module: FileTracker using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.999 W React: There is no generated module helper for module: RNGeocoder using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:58.999 W React: There is no generated module helper for module: AudioManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:59.000 W React: There is no generated module helper for module: RNUrlRequest using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:59.000 W React: There is no generated module helper for module: CortanaSignals using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:59.000 W React: There is no generated module helper for module: AssetReader using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:59.000 W React: There is no generated module helper for module: PermissionsManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:59.000 W React: There is no generated module helper for module: AdvertisementUtilities using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:59.000 W React: There is no generated module helper for module: FileEncryptionNative using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:59.001 W React: There is no generated module helper for module: ContextMenuAndroid using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:59.001 W React: There is no generated module helper for module: DeviceUtilities using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:59.001 W React: There is no generated module helper for module: AirMapModule using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:59.001 W React: There is no generated module helper for module: RNKeychainManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:59.001 W React: There is no generated module helper for module: RNBackgroundTimer using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:59.001 W React: There is no generated module helper for module: RNHockeyApp using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:59.002 W React: There is no generated module helper for module: ShareSheet using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:59.002 W React: There is no generated module helper for module: SKPSkypeMessageTextInputModule using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:59.002 W React: There is no generated module helper for module: ImagePickerManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:59.002 W React: There is no generated module helper for module: RNPushAndroid using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:59.002 W React: There is no generated module helper for module: UrlUtil using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:59.002 W React: There is no generated module helper for module: CallIntent using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:59.002 W React: There is no generated module helper for module: ShareToApp using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:59.002 W React: There is no generated module helper for module: SourceCode using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:59.003 W React: There is no generated module helper for module: RNManualFileCache using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:59.003 W React: There is no generated module helper for module: RNGLContext using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-08 06:07:59.024 I SmsHandlingContext: init()
06-08 06:07:59.025 I SkypeCameraModule: SkypeCameraModule initialize
06-08 06:07:59.028 W ReactApp: registerMemoryTrimmable current size: 0
06-08 06:07:59.028 W ReactApp: registerMemoryTrimmable current size: 1
06-08 06:07:59.039 I AudioManagerModule: initialize (causeId 1b3e4c94)
06-08 06:07:59.040 I AudioManagerModule: AudioManagerModule.initialize took 1ms
06-08 06:07:59.041 I AudioOptions: initialize (causeId 1b3e4c94)
06-08 06:07:59.043 I WiredHeadsetReceiver: Registered receiver
06-08 06:07:59.044 I WiredHeadsetReceiver: addListener (causeId: 1b3e4c94)
06-08 06:07:59.044 I AudioOptions: WiredHeadsetReceiver.headsetStateChanged UNPLUGGED (causeId 1b3e4c94)
06-08 06:07:59.046 I BluetoothReceiver: Received sticky intent android.media.ACTION_SCO_AUDIO_STATE_UPDATED
06-08 06:07:59.046 I BluetoothReceiver: Registered receiver
06-08 06:07:59.046 I BluetoothReceiver: onReceive action android.media.ACTION_SCO_AUDIO_STATE_UPDATED (causeId 9515b8af)
06-08 06:07:59.046 I BluetoothReceiver: handleScoAudioStateChange prevState: -1 state: 0 (causeId: 9515b8af)
06-08 06:07:59.046 I BluetoothReceiver: loadAlreadyConnectedDevices (causeId: 1b3e4c94)
06-08 06:07:59.047 I BluetoothReceiver: scoDisconnected
06-08 06:07:59.048 I BluetoothReceiver: onReceive action android.media.ACTION_SCO_AUDIO_STATE_UPDATED (causeId a2e176a0)
06-08 06:07:59.049 I BluetoothReceiver: handleScoAudioStateChange prevState: -1 state: 0 (causeId: a2e176a0)
06-08 06:07:59.049 I BluetoothReceiver: scoDisconnected
06-08 06:07:59.049 I BluetoothReceiver: onReceive action android.media.SCO_AUDIO_STATE_CHANGED (causeId ea17b5d8)
06-08 06:07:59.050 I BluetoothReceiver: handleScoAudioStateChange prevState: 0 state: 0 (causeId: ea17b5d8)
06-08 06:07:59.050 I BluetoothReceiver: scoDisconnected
06-08 06:07:59.050 I BluetoothReceiver: addListener (causeId: 1b3e4c94)
06-08 06:07:59.050 I BluetoothReceiver: createServiceListener (causeId: 1b3e4c94)
06-08 06:07:59.068 I ModernAudioDeviceMonitor: addListener (causeId: 1b3e4c94)
06-08 06:07:59.068 I AudioOptions: ModernAudioDeviceMonitor.availableAudioDeviceTypesChanged headphones: false usb: false (causeId 1b3e4c94)
06-08 06:07:59.077 I TelephoneStateListener: Registering phone state listener (causeId 1b3e4c94)
06-08 06:07:59.079 I ModernAudioDeviceMonitor: initialization headphones: false, usb: false, devices: [[1:TYPE_BUILTIN_EARPIECE], [2:TYPE_BUILTIN_SPEAKER], [6:TYPE_BUILTIN_MIC], [8:TYPE_TELEPHONY]] (causeId: c1c8196a)
06-08 06:07:59.080 I AudioManagerModule: Sending output changed event to EARPIECE (causeId 1b3e4c94)
06-08 06:07:59.080 I ModernAudioDeviceMonitor: onAudioDevicesAdded headphones: false, usb: false, devices: [[1:TYPE_BUILTIN_EARPIECE], [2:TYPE_BUILTIN_SPEAKER], [6:TYPE_BUILTIN_MIC], [8:TYPE_TELEPHONY]] (causeId: 75c09b13)
06-08 06:07:59.081 I AudioManagerModule: calcSettingsAndUpdate: Skipping - not initialized (causeId: 1b3e4c94)
06-08 06:07:59.083 I ModernAudioDeviceMonitor: onAudioDevicesAdded headphones: false, usb: false, devices: [[1:TYPE_BUILTIN_EARPIECE], [2:TYPE_BUILTIN_SPEAKER], [6:TYPE_BUILTIN_MIC], [8:TYPE_TELEPHONY]] (causeId: 5fd01c2f)
06-08 06:07:59.083 I TokenShareModule: getAccounts() called, returned with list size 0
06-08 06:07:59.083 I AudioManagerModule: calcSettingsAndUpdate: Skipping - not initialized (causeId: 1b3e4c94)
06-08 06:07:59.085 I AudioManagerModule: TelephoneStateListener.init took 12ms
06-08 06:07:59.086 I TelephoneStateListener: onCallStateChanged 0 (causeId a5d39037)
06-08 06:07:59.878 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'StaticTask.OnAppUpdated'
06-08 06:07:59.881 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'StaticTask.OnAppUpdatedRetry'
06-08 06:07:59.925 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'SignInOnUserSessionConnected'
06-08 06:07:59.925 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'SignInOnUserSessionConnectedRetry'
06-08 06:07:59.926 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'SignInOnDefaultMSAConnected'
06-08 06:07:59.926 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'SignInOnDefaultMSAConnectedRetry'
06-08 06:07:59.928 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'OnMaintenanceWindowStart'
06-08 06:07:59.928 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'OnMaintenanceWindowStartRetry'
06-08 06:07:59.951 I RNAppUpgrade: Getting app launch attribution state = false
06-08 06:07:59.952 I RNAppUpgrade: hasOldSessionPreferences:false
06-08 06:07:59.957 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] Preparing to handle App Upgrade Event
06-08 06:07:59.958 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] Preparing to handle Rtc Wake Event
06-08 06:07:59.959 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] _setUpAppLaunchStateChangeListener
06-08 06:07:59.960 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] _setUpNoticationClickListener
06-08 06:07:59.963 I RNAppUpgrade: initialize
06-08 06:07:59.963 I UpgradeContext: acquireWakeLock taskId 2
06-08 06:07:59.965 I SimpleWakefulService: Acquire WAKE_LOCK for taskId: 2 with startId: 2
06-08 06:07:59.967 I RNAppUpgrade: processPendingIntents
06-08 06:07:59.967 I RNAppUpgrade: processPendingIntents:delayedIntentQueue size(1)
06-08 06:07:59.968 I RNAppUpgrade: processPendingIntent with action: android.intent.action.MY_PACKAGE_REPLACED
06-08 06:07:59.968 I RNAppUpgrade: App Received Intent with action - android.intent.action.MY_PACKAGE_REPLACED
06-08 06:07:59.972 I RNAppUpgrade: Emitted event for intent with action android.intent.action.MY_PACKAGE_REPLACED with eventOptions: {"notificationId":0,"scheduledWakeUpTime":0,"taskId":1}
06-08 06:07:59.973 I RNAppUpgrade: initialize
06-08 06:08:00.067 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Locale initialized to [en_CA]
06-08 06:08:00.068 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Country code is [CA]
06-08 06:08:00.082 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Device Id: fkgXjGl17eI
06-08 06:08:00.083 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Device Manufacturer: samsung
06-08 06:08:00.084 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Device Model: SM-G955W
06-08 06:08:00.084 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Device OS version: 8.0.0
06-08 06:08:00.085 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] App version: 8.23.0.10
06-08 06:08:00.085 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] App activation state: Background
06-08 06:08:00.094 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.GenericUnsafe] Startup Phase 1 duration: 2426ms
06-08 06:08:00.104 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.GenericUnsafe] Startup Phase 2 duration: 883ms
06-08 06:08:00.114 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Starting: HockeyAppService
06-08 06:08:00.122 I ReactHockeyApp: HockeyApp - initializing configuration
06-08 06:08:00.122 I ReactNativeJS: [#ffffffff-S] [TRACE] [JS.HockeyApp] Ignoring check for updates - PUBLIC build
06-08 06:08:00.124 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Finish: HockeyAppService: 10ms
06-08 06:08:00.129 I React: Check for new app crashes
06-08 06:08:00.142 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Starting: CrashStatusStore
06-08 06:08:00.144 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.GenericUnsafe] RN Entry
06-08 06:08:00.153 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] App Upgrade Event Received with token 1
06-08 06:08:00.154 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] _onAppUpgradeEventReceived:_getAppLaunchState:begin: 1
06-08 06:08:00.156 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] Last app launch time: undefined
06-08 06:08:00.205 I ReactNativeJS: [#ffffffff-S] [TRACE] [JS.HockeyApp] Last launch crashed: false
06-08 06:08:00.206 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Finish: CrashStatusStore: 65ms
06-08 06:08:00.209 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] SkypeId missing in Storage
06-08 06:08:00.219 I RNAppUpgrade: hasUserDatabase:begin
06-08 06:08:00.220 I RNAppUpgrade: hasUserDatabase:reject
06-08 06:08:00.257 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.GenericUnsafe] ECS - fetching parameters:{"OSVer":26,"ClientID":"fkgXjGl17eI","Manufacturer":"samsung","Model":"SM-G955W","Chipset":"qcom","CPUCount":8,"CPUSpeedMHz":2361.6,"Language":"en","Locale":"en-GB","NetworkMCCCode":"302","NetworkMNCCode":"610"}
06-08 06:08:00.269 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.GenericUnsafe] ECS - Delaying config fetch until the app is active (or background fetch is allowed)
06-08 06:08:00.382 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] Setting App Launch State NeverLaunched
06-08 06:08:00.443 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.ConsoleSink] initialized and paused
06-08 06:08:00.451 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.ConsoleSink] resumed
06-08 06:08:00.565 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] _getAppLaunchState:subscribe:fired:0
06-08 06:08:00.567 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] _getAppLaunchState:subscribe:fired:0
06-08 06:08:00.568 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] _onAppUpgradeEventReceived:launchedState:NeverLaunched
06-08 06:08:00.569 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] _onAppUpgradeEventReceived:_getAppLaunchState:end: 1
06-08 06:08:00.569 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] _getOEMConfigUsingBackgroundECSFetch, acceptStale:true
06-08 06:08:00.574 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] _subscribeAndFetchEcs
06-08 06:08:00.586 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] ECSConfig:Subscribing for fresh ECS
06-08 06:08:00.595 E CredentialsFetcher: Can't parse xml
06-08 06:08:00.595 E CredentialsFetcher: /data/user/0/com.skype.raider/files/shared.xml (No such file or directory)
06-08 06:08:00.595 E CredentialsFetcher: 	java.io.FileInputStream.open0(FileInputStream.java:-2)
06-08 06:08:00.595 E CredentialsFetcher: 	java.io.FileInputStream.open(FileInputStream.java:200)
06-08 06:08:00.595 E CredentialsFetcher: 	java.io.FileInputStream.<init>(FileInputStream.java:150)
06-08 06:08:00.595 E CredentialsFetcher: 	com.skype.credentials.CredentialsFetcher.a(SourceFile:44)
06-08 06:08:00.595 E CredentialsFetcher: 	com.skype.credentials.SkypeCredentialsFetcherModule.fetchUserInfo(SourceFile:46)
06-08 06:08:00.595 E CredentialsFetcher: 	java.lang.reflect.Method.invoke(Method.java:-2)
06-08 06:08:00.595 E CredentialsFetcher: 	com.facebook.react.bridge.q.a(SourceFile:366)
06-08 06:08:00.595 E CredentialsFetcher: 	com.facebook.react.bridge.JavaModuleWrapper$b.invoke(SourceFile:283)
06-08 06:08:00.595 E CredentialsFetcher: 	com.facebook.react.bridge.JavaModuleWrapper.invoke(SourceFile:176)
06-08 06:08:00.595 E CredentialsFetcher: 	com.facebook.react.bridge.queue.NativeRunnable.run(SourceFile:-2)
06-08 06:08:00.595 E CredentialsFetcher: 	android.os.Handler.handleCallback(Handler.java:789)
06-08 06:08:00.595 E CredentialsFetcher: 	android.os.Handler.dispatchMessage(Handler.java:98)
06-08 06:08:00.595 E CredentialsFetcher: 	com.facebook.react.bridge.queue.a.dispatchMessage(SourceFile:31)
06-08 06:08:00.595 E CredentialsFetcher: 	android.os.Looper.loop(Looper.java:164)
06-08 06:08:00.595 E CredentialsFetcher: 	com.facebook.react.bridge.queue.MessageQueueThreadImpl$3.run(SourceFile:194)
06-08 06:08:00.595 E CredentialsFetcher: 	java.lang.Thread.run(Thread.java:764)
06-08 06:08:00.600 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] AppBootstrapperNative._fallbackToLogin reason: NoSkypeIdFound
06-08 06:08:00.640 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Starting: ResponsiveWidthStore
06-08 06:08:00.645 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.ResponsiveWidthStore] New width: 411.42857142857144 causeId: bbaa459b
06-08 06:08:00.646 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.ResponsiveWidthStore] New Responsive Width: 0 causeId: bbaa459b
06-08 06:08:00.647 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.ResponsiveWidthStore] New height: 797.7142857142857 causeId: bbaa459b
06-08 06:08:00.659 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Finish: ResponsiveWidthStore: 20ms
06-08 06:08:00.660 I DeviceUtilities: DeviceUtilities: currentOrientation
06-08 06:08:00.660 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Starting: StatusBarManager, Deps Finish: 21ms
06-08 06:08:00.739 W React: StatusBarModule: Ignored status bar change, current activity is null.
06-08 06:08:00.748 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Finish: StatusBarManager: 87ms
06-08 06:08:00.748 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Starting: SafeAreaStore, Deps Finish: 109ms
06-08 06:08:00.750 W React: StatusBarModule: Ignored status bar change, current activity is null.
06-08 06:08:00.751 W React: StatusBarModule: Ignored status bar change, current activity is null.
06-08 06:08:00.751 I DeviceUtilities: DeviceUtilities: statusBarHeight
06-08 06:08:00.752 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Finish: SafeAreaStore: 3ms
06-08 06:08:00.755 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Starting: ReportedConnectivityStore
06-08 06:08:00.757 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Finish: ReportedConnectivityStore: 3ms
06-08 06:08:00.758 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] WelcomeScreen waiting for ECS config with timeout: 1000
06-08 06:08:00.765 W ReactNativeJS: [#ffffffff-u] [WARN] [JS.ResponsiveWidthStore] DeviceUtilities.currentOrientation failed: [pii<E...>] causeId: bbaa459b
06-08 06:08:00.767 W ReactNativeJS: [#ffffffff-u] [WARN] [JS.GenericUnsafe] SafeAreaStore statusBarHeight failed: [pii<E...>]
06-08 06:08:00.772 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.NetworkConnectionStore]  _fetchNetworkType() type: Unknown
06-08 06:08:00.775 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.ReportedConnectivityStore] connectivity has changed: Connected = false
06-08 06:08:01.026 I HttpLoggingInterceptor: Http succeeded, request: GET config.edge.skype.com. Response: 200  (432 ms, -1 body)
06-08 06:08:01.072 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.GenericUnsafe] ECS - Config fetch complete
06-08 06:08:03.697 W ReactMethodWatchdog: Method TokenShareModule.getToken invocation took too long: 2571ms
06-08 06:08:03.698 I RNAppUpgrade: onUpgradeWakeUpForActivationExperiment
06-08 06:08:03.706 W ReactNativeJS: [#ffffffff-u] [WARN] [JS.SISU] SSO did not retrieve any accounts: Error: No refresh token was found
06-08 06:08:03.811 I ActivationExperiment: ActivationOptions{"ecsConfig":{"sendAppUpgradeTelemetry":true,"upgradeNotification":{"appParameters":{"appStateList":["Launched"],"maxWakeAttempts":3,"minHoursSinceLaunch":72,"wakeIntervalSecs":259200},"enabled":false,"enabledExperiments":["hero2lte","j5lte","dreamlte","on5xelte","zeroflte","j7xeltexx"],"notificationTimingInfo":{"scheduleHourOfDay":19}}},"isInsidersBuild":false,"lastLaunchTime":-1,"launchState":"NeverLaunched","notificationMeta":{"imageStyle":"None","imageUri":"https://secure.skypeassets.com/content/dam/scom/app/notifications/ensure_network_image.png","notificationStyle":"TextOnly2","notificationTemplateType":"Default","subtitle":"Turn everyday chats into memorable moments","title":"Meet your new Skype"},"notificationState":"NotScheduled","notificationStyle":"TextOnly2","partnerPreInstallId":"534","scheduleWakeUpTime":0}
06-08 06:08:03.812 I ActivationExperiment: onAppWakeUp, woke up at: Friday, June 8, 2018 at 12:08 AM with AppLaunchState NeverLaunched, wakeUpReason(Upgrade)
06-08 06:08:03.812 I ActivationExperiment: isEligibleToStartExperiment, SAMSUNG_PREINSTALL
06-08 06:08:03.837 I ActivationExperiment: loadFromDisk:null, timeTaken(24 ms)
06-08 06:08:03.839 I ActivationExperiment: isEligibleToExecuteExperiment: upgradeNotification not enabled
06-08 06:08:03.839 I ActivationExperiment: scheduleWakeUpForActivationExperiment: schedule next wake up after: 327600 secs, app will wake up on Monday, June 11, 2018 at 7:08 PM
06-08 06:08:03.840 I ActivationExperiment: cancelPendingRtcWake
06-08 06:08:03.855 I ActivationExperiment: persistToDisk: SAVING, payload({"experimentList":[],"schemaVersion":"v1","totalWakeAttempts":1,"wakeUpList":[{"reason":"Upgrade","status":"NextWakeUpScheduled","time":1528438083838},{"reason":"RtcWakeUp","status":"WakeUpPending","time":1528765683839}]})
06-08 06:08:03.855 I ActivationExperiment: scheduleWakeUpForActivationExperiment: scheduled attempt(1), TimeTaken(16 ms)
06-08 06:08:03.866 W ReactMethodWatchdog: Method RNAppUpgrade.onUpgradeWakeUpForActivationExperiment invocation took too long: 169ms
06-08 06:08:03.934 I UpgradeContext: releaseWakeLock taskId 1
06-08 06:08:03.938 I SimpleWakefulService: Release WAKE_LOCK for taskId: 1 with startId: 3
06-08 06:08:03.943 I SimpleWakefulService: Removing Stop message
06-08 06:08:04.554 I HttpLoggingInterceptor: Http succeeded, request: POST browser.pipe.aria.microsoft.com (1852 body). Response: 200 OK (618 ms, 0 body)
06-08 06:08:04.560 I HttpLoggingInterceptor: Http succeeded, request: POST browser.pipe.aria.microsoft.com (1372 body). Response: 200 OK (677 ms, 0 body)
06-08 06:08:07.471 I RNSlimcore: Clearing old logs
06-08 06:08:07.476 I SkyLibManager[TERMINATED:null]: clearOldLogs found 0 potential log files
06-08 06:08:12.184 W PushHandlingService: wake lock wasn't released in its processing time. Check missing Stop push handling log statement.
06-08 06:08:12.185 I RNBackgroundExecution: completeWakefulIntentAfterAllWakeLocks(PushHandling:endStart), wakelock id: f7820852-8ee9-4a57-9e6b-581ddbd1c2e3, at: 1528438092185
06-08 06:08:12.186 I RNBackgroundExecution: releaseAll(PushHandling:endStart), forcing release: 0, ids: [], at: 1528438092186, because last ID or Wakeful Service is being released
06-08 06:08:12.188 I PushHandlingService: There are no intents to complete anymore. Stop pushId:1, startId: 1
06-08 06:08:12.190 I PushHandlingService: Service destroyed
06-08 06:08:15.008 I UpgradeContext: releaseWakeLock taskId 2
06-08 06:08:15.017 I SimpleWakefulService: Release WAKE_LOCK for taskId: 2 with startId: 4
06-08 06:08:15.032 I SimpleWakefulService: Removing Stop message
06-08 06:08:15.038 I SimpleWakefulService: Service destroyed
06-09 01:11:40.207 W ReactHockeyApp: RNHockeyApp: Failed to get existing metadata
06-09 01:11:40.207 W ReactHockeyApp: /data/user/0/com.skype.raider/files/HockeyAppCrashMetadata.json (No such file or directory)
06-09 01:11:40.207 W ReactHockeyApp: 	java.io.FileInputStream.open0(FileInputStream.java:-2)
06-09 01:11:40.207 W ReactHockeyApp: 	java.io.FileInputStream.open(FileInputStream.java:200)
06-09 01:11:40.207 W ReactHockeyApp: 	java.io.FileInputStream.<init>(FileInputStream.java:150)
06-09 01:11:40.207 W ReactHockeyApp: 	android.app.ContextImpl.openFileInput(ContextImpl.java:520)
06-09 01:11:40.207 W ReactHockeyApp: 	android.content.ContextWrapper.openFileInput(ContextWrapper.java:200)
06-09 01:11:40.207 W ReactHockeyApp: 	com.skype.hockeyapp.SkypeCrashListener.f(SourceFile:139)
06-09 01:11:40.207 W ReactHockeyApp: 	com.skype.hockeyapp.SkypeCrashListener.<init>(SourceFile:48)
06-09 01:11:40.207 W ReactHockeyApp: 	com.skype.hockeyapp.SkypeCrashListener.a(SourceFile:43)
06-09 01:11:40.207 W ReactHockeyApp: 	com.skype.hockeyapp.SkypeCrashManager.a(SourceFile:37)
06-09 01:11:40.207 W ReactHockeyApp: 	com.skype4life.SkypeApplication.onCreate(SourceFile:1042)
06-09 01:11:40.207 W ReactHockeyApp: 	android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1125)
06-09 01:11:40.207 W ReactHockeyApp: 	android.app.ActivityThread.handleBindApplication(ActivityThread.java:6056)
06-09 01:11:40.207 W ReactHockeyApp: 	android.app.ActivityThread.-wrap1(null:0)
06-09 01:11:40.207 W ReactHockeyApp: 	android.app.ActivityThread$H.handleMessage(ActivityThread.java:1764)
06-09 01:11:40.207 W ReactHockeyApp: 	android.os.Handler.dispatchMessage(Handler.java:105)
06-09 01:11:40.207 W ReactHockeyApp: 	android.os.Looper.loop(Looper.java:164)
06-09 01:11:40.207 W ReactHockeyApp: 	android.app.ActivityThread.main(ActivityThread.java:6938)
06-09 01:11:40.207 W ReactHockeyApp: 	java.lang.reflect.Method.invoke(Method.java:-2)
06-09 01:11:40.207 W ReactHockeyApp: 	com.android.internal.os.Zygote$MethodAndArgsCaller.run(Zygote.java:327)
06-09 01:11:40.207 W ReactHockeyApp: 	com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1374)
06-09 01:11:40.225 I DumpUploader: Preparing check for new crash dumps
06-09 01:11:40.227 I ReactApp: onCreate start
06-09 01:11:40.228 I DumpUploader: Started check for new crash dumps
06-09 01:11:40.230 I DumpUploader: Marking dumps as known: 
06-09 01:11:40.234 I ReactApp: configureViewPools took 0ms
06-09 01:11:40.262 I ReactApp: configureOkHttp took 27ms
06-09 01:11:40.263 I ReactApp: configureStetho took 0ms
06-09 01:11:40.302 I ReactApp: configureYoga took 39ms
06-09 01:11:40.306 I ReactApp: CsiManager.onCreate took 2ms
06-09 01:11:40.405 I ReactApp: mReactNativeHost.getReactInstanceManager took 99ms
06-09 01:11:40.406 I ReactApp: onCreate complete in 306ms
06-09 01:11:40.406 I React: Creating react context.
06-09 01:11:40.422 I SkypeCameraViewManager: init
06-09 01:11:40.451 I GradientImagePackage: createViewManagers
06-09 01:11:40.456 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.ink.AdditiveSurfaceViewManager
06-09 01:11:40.463 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.ink.AdditiveSurfaceViewShadowNode
06-09 01:11:40.476 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.uimanager.h
06-09 01:11:40.489 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.text.g
06-09 01:11:40.506 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.textinput.i
06-09 01:11:40.529 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.art.c
06-09 01:11:40.531 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.art.b
06-09 01:11:40.533 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.art.a
06-09 01:11:40.536 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.progressbar.b
06-09 01:11:40.537 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.text.frescosupport.a
06-09 01:11:40.539 W ViewManagerPropertyUpdater: Could not find generated setter for class com.brentvatne.react.ReactVideoViewManager
06-09 01:11:40.544 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skpcamera.SkypeCameraViewManager
06-09 01:11:40.558 W ViewManagerPropertyUpdater: Could not find generated setter for class com.customkeyboard.CustomKeyboardViewManager
06-09 01:11:40.569 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.slimcore.video.RNCallingVideoViewManager
06-09 01:11:40.571 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.slimcore.video.RNCallingVideoViewLocalManager
06-09 01:11:40.575 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.react.mediapicker.MediaPickerViewManager
06-09 01:11:40.581 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.react.mediapicker.c
06-09 01:11:40.586 I ActivationExperiment: loadFromDisk:{"experimentList":[],"schemaVersion":"v1","totalWakeAttempts":1,"wakeUpList":[{"reason":"Upgrade","status":"NextWakeUpScheduled","time":1528438083838},{"reason":"RtcWakeUp","status":"WakeUpPending","time":1528765683839}]}, timeTaken(3 ms)
06-09 01:11:40.587 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.skypemessagetextinput.view.RNViewManager
06-09 01:11:40.591 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.skypemessagetextinput.view.c
06-09 01:11:40.592 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.reactnativesprites.SpriteViewManager
06-09 01:11:40.595 W ViewManagerPropertyUpdater: Could not find generated setter for class com.projectseptember.RNGL.GLCanvasManager
06-09 01:11:40.598 W ViewManagerPropertyUpdater: Could not find generated setter for class com.github.alinz.reactnativewebviewbridge.WebViewBridgeManager
06-09 01:11:40.606 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapCalloutManager
06-09 01:11:40.606 I ActivationExperiment: cancelPendingRtcWake
06-09 01:11:40.609 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapMarkerManager
06-09 01:11:40.614 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapPolylineManager
06-09 01:11:40.617 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapPolygonManager
06-09 01:11:40.620 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapCircleManager
06-09 01:11:40.624 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapManager
06-09 01:11:40.631 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapLiteManager
06-09 01:11:40.633 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapUrlTileManager
06-09 01:11:40.635 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.react.videofxp.VideoFXPViewManager
06-09 01:11:40.639 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.virtualmessageview.VirtualMessageViewControllerManager
06-09 01:11:40.641 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.react.clippedview.ClippedViewManager
06-09 01:11:40.644 W ViewManagerPropertyUpdater: Could not find generated setter for class com.BV.LinearGradient.LinearGradientManager
06-09 01:11:40.646 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.lottie.LottieAnimationViewManager
06-09 01:11:40.650 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.react.gradientimage.GradientImageViewManager
06-09 01:11:40.653 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.qrcode.QRCodeViewManager
06-09 01:11:40.656 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.camera.imagefilter.ImageFilterManager
06-09 01:11:40.955 W JavaModuleHelper: Could not find generated custom module provider
06-09 01:11:40.956 W React: There is no generated module helper for module: ImagePickerManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.957 W React: There is no generated module helper for module: RNCookieManagerAndroid using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.958 W React: There is no generated module helper for module: TimeZoneManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.958 W React: There is no generated module helper for module: ShareSheet using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.958 W React: There is no generated module helper for module: RNDocumentPicker using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.958 W React: There is no generated module helper for module: SoundRecorder using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.959 W React: There is no generated module helper for module: DeviceUtilities using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.959 W React: There is no generated module helper for module: FrescoModule using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.959 W React: There is no generated module helper for module: EnvironmentInfo using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.959 W React: There is no generated module helper for module: ExternalBrowser using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.959 W React: There is no generated module helper for module: SplashScreenNotifier using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.959 W React: There is no generated module helper for module: CortanaSignals using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.959 W React: There is no generated module helper for module: RNReload using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.960 W React: There is no generated module helper for module: TokenShareModule using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.960 W React: There is no generated module helper for module: AdvertisementUtilities using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.960 W React: There is no generated module helper for module: ZipUtil using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.960 W React: There is no generated module helper for module: FileEncryptionNative using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.960 W React: There is no generated module helper for module: RNNetworkInfo using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.960 W React: There is no generated module helper for module: Adjust using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.960 W React: There is no generated module helper for module: AssetReader using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.960 W React: There is no generated module helper for module: RNBackgroundTimer using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.961 W React: There is no generated module helper for module: PermissionsManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.961 W React: There is no generated module helper for module: CallMonitor using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.961 W React: There is no generated module helper for module: RNUrlRequest using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.961 W React: There is no generated module helper for module: ContextMenuAndroid using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.962 W React: There is no generated module helper for module: RNPushAndroid using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.962 W React: There is no generated module helper for module: ShareToApp using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.962 W React: There is no generated module helper for module: SKPSkypeMessageTextInputModule using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.962 W React: There is no generated module helper for module: Contacts using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.963 W React: There is no generated module helper for module: CustomKeyboard using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.963 W React: There is no generated module helper for module: RNSkypeCredentialsFetcher using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.963 W React: There is no generated module helper for module: SoundPlayer using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.963 W React: There is no generated module helper for module: AndroidSmsManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.964 W React: There is no generated module helper for module: UrlUtil using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.964 W React: There is no generated module helper for module: SkypeCamera using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.964 W React: There is no generated module helper for module: RNKeychainManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.964 W React: There is no generated module helper for module: VideoFXP using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.964 W React: There is no generated module helper for module: RNGLContext using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.964 W React: There is no generated module helper for module: RNGraphicsContext using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.965 W React: There is no generated module helper for module: FileTracker using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.965 W React: There is no generated module helper for module: FingerprintingLib using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.965 W React: There is no generated module helper for module: IncomingCallInteractionManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.966 W React: There is no generated module helper for module: DeviceSettings using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.966 W React: There is no generated module helper for module: SourceCode using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.966 W React: There is no generated module helper for module: RNSlimcore using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.966 W React: There is no generated module helper for module: CallIntent using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.968 W React: There is no generated module helper for module: ImageResizerAndroid using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.969 W React: There is no generated module helper for module: RNAppUpgrade using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.969 W React: There is no generated module helper for module: ExtendedAppState using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.969 W React: There is no generated module helper for module: RNHockeyApp using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.969 W React: There is no generated module helper for module: RNBackgroundExecution using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.969 W React: There is no generated module helper for module: AirMapModule using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.970 W React: There is no generated module helper for module: CampaignReceiver using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.970 W React: There is no generated module helper for module: AndroidBadges using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.970 W React: There is no generated module helper for module: RNCommandInvoker using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.970 W React: There is no generated module helper for module: StyleTransfer using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.970 W React: There is no generated module helper for module: RNManualFileCache using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.970 W React: There is no generated module helper for module: SnapshotManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.971 W React: There is no generated module helper for module: RNStorage using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.971 W React: There is no generated module helper for module: NativeEntropy using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.971 W React: There is no generated module helper for module: DeviceInfo using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.972 W React: There is no generated module helper for module: ClientLogging using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.972 W React: There is no generated module helper for module: RNViewConfig using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.972 W React: There is no generated module helper for module: RNGeocoder using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.972 W React: There is no generated module helper for module: MediaPicker using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.973 W React: There is no generated module helper for module: PlatformConstants using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:40.974 W React: There is no generated module helper for module: AudioManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 01:11:41.034 I SmsHandlingContext: init()
06-09 01:11:41.038 W ReactApp: registerMemoryTrimmable current size: 0
06-09 01:11:41.038 W ReactApp: registerMemoryTrimmable current size: 1
06-09 01:11:41.047 I SkypeCameraModule: SkypeCameraModule initialize
06-09 01:11:41.049 I AudioManagerModule: initialize (causeId 41391236)
06-09 01:11:41.049 I AudioManagerModule: AudioManagerModule.initialize took 0ms
06-09 01:11:41.050 I AudioOptions: initialize (causeId 41391236)
06-09 01:11:41.056 I WiredHeadsetReceiver: Registered receiver
06-09 01:11:41.056 I WiredHeadsetReceiver: addListener (causeId: 41391236)
06-09 01:11:41.057 I AudioOptions: WiredHeadsetReceiver.headsetStateChanged UNPLUGGED (causeId 41391236)
06-09 01:11:41.060 I BluetoothReceiver: Received sticky intent android.media.ACTION_SCO_AUDIO_STATE_UPDATED
06-09 01:11:41.060 I BluetoothReceiver: Registered receiver
06-09 01:11:41.060 I BluetoothReceiver: loadAlreadyConnectedDevices (causeId: 41391236)
06-09 01:11:41.061 I BluetoothReceiver: onReceive action android.media.ACTION_SCO_AUDIO_STATE_UPDATED (causeId f1c1a814)
06-09 01:11:41.061 I BluetoothReceiver: handleScoAudioStateChange prevState: -1 state: 0 (causeId: f1c1a814)
06-09 01:11:41.061 I BluetoothReceiver: scoDisconnected
06-09 01:11:41.065 I BluetoothReceiver: createServiceListener (causeId: 41391236)
06-09 01:11:41.070 I BluetoothReceiver: onReceive action android.media.SCO_AUDIO_STATE_CHANGED (causeId ca4323c7)
06-09 01:11:41.076 I BluetoothReceiver: handleScoAudioStateChange prevState: 0 state: 0 (causeId: ca4323c7)
06-09 01:11:41.076 I BluetoothReceiver: scoDisconnected
06-09 01:11:41.085 I ModernAudioDeviceMonitor: addListener (causeId: 41391236)
06-09 01:11:41.101 I AudioManagerModule: Sending output changed event to EARPIECE (causeId 41391236)
06-09 01:11:41.127 I AudioOptions: ModernAudioDeviceMonitor.availableAudioDeviceTypesChanged headphones: false usb: false (causeId 41391236)
06-09 01:11:41.103 I BluetoothReceiver: onReceive action android.media.ACTION_SCO_AUDIO_STATE_UPDATED (causeId fb2db6a4)
06-09 01:11:41.128 I BluetoothReceiver: handleScoAudioStateChange prevState: -1 state: 0 (causeId: fb2db6a4)
06-09 01:11:41.128 I BluetoothReceiver: scoDisconnected
06-09 01:11:41.128 I BluetoothReceiver: addListener (causeId: 41391236)
06-09 01:11:41.128 I ModernAudioDeviceMonitor: initialization headphones: false, usb: false, devices: [[1:TYPE_BUILTIN_EARPIECE], [2:TYPE_BUILTIN_SPEAKER], [6:TYPE_BUILTIN_MIC], [8:TYPE_TELEPHONY]] (causeId: 56efa4c6)
06-09 01:11:41.088 I TelephoneStateListener: Registering phone state listener (causeId 41391236)
06-09 01:11:41.100 I TokenShareModule: getAccounts() called, returned with list size 0
06-09 01:11:41.128 I AudioManagerModule: calcSettingsAndUpdate: Skipping - not initialized (causeId: 41391236)
06-09 01:11:41.129 I ModernAudioDeviceMonitor: onAudioDevicesAdded headphones: false, usb: false, devices: [[1:TYPE_BUILTIN_EARPIECE], [2:TYPE_BUILTIN_SPEAKER], [6:TYPE_BUILTIN_MIC], [8:TYPE_TELEPHONY]] (causeId: 1e1711ff)
06-09 01:11:41.130 I ModernAudioDeviceMonitor: onAudioDevicesAdded headphones: false, usb: false, devices: [[1:TYPE_BUILTIN_EARPIECE], [2:TYPE_BUILTIN_SPEAKER], [6:TYPE_BUILTIN_MIC], [8:TYPE_TELEPHONY]] (causeId: 6c6a1e79)
06-09 01:11:41.130 I AudioManagerModule: calcSettingsAndUpdate: Skipping - not initialized (causeId: 41391236)
06-09 01:11:41.136 I AudioManagerModule: TelephoneStateListener.init took 48ms
06-09 01:11:41.138 I TelephoneStateListener: onCallStateChanged 0 (causeId a0ffe102)
06-09 01:11:41.948 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'StaticTask.OnAppUpdated'
06-09 01:11:41.951 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'StaticTask.OnAppUpdatedRetry'
06-09 01:11:41.998 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'SignInOnUserSessionConnected'
06-09 01:11:41.999 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'SignInOnUserSessionConnectedRetry'
06-09 01:11:41.999 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'SignInOnDefaultMSAConnected'
06-09 01:11:42.000 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'SignInOnDefaultMSAConnectedRetry'
06-09 01:11:42.002 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'OnMaintenanceWindowStart'
06-09 01:11:42.002 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'OnMaintenanceWindowStartRetry'
06-09 01:11:42.031 I RNAppUpgrade: Getting app launch attribution state = false
06-09 01:11:42.033 I RNAppUpgrade: hasOldSessionPreferences:false
06-09 01:11:42.039 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] Preparing to handle App Upgrade Event
06-09 01:11:42.039 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] Preparing to handle Rtc Wake Event
06-09 01:11:42.040 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] _setUpAppLaunchStateChangeListener
06-09 01:11:42.042 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] _setUpNoticationClickListener
06-09 01:11:42.045 I RNAppUpgrade: initialize
06-09 01:11:42.045 I UpgradeContext: acquireWakeLock taskId 1
06-09 01:11:42.050 I SimpleWakefulService: Service created
06-09 01:11:42.051 I SimpleWakefulService: Acquire WAKE_LOCK for taskId: 1 with startId: 1
06-09 01:11:42.057 I RNAppUpgrade: processPendingIntents
06-09 01:11:42.057 I RNAppUpgrade: processPendingIntents:delayedIntentQueue size(0)
06-09 01:11:42.058 I RNAppUpgrade: initialize
06-09 01:11:42.162 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Locale initialized to [en_CA]
06-09 01:11:42.163 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Country code is [CA]
06-09 01:11:42.181 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Device Id: fkgXjGl17eI
06-09 01:11:42.181 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Device Manufacturer: samsung
06-09 01:11:42.182 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Device Model: SM-G955W
06-09 01:11:42.183 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Device OS version: 8.0.0
06-09 01:11:42.183 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] App version: 8.23.0.10
06-09 01:11:42.183 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] App activation state: Background
06-09 01:11:42.196 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.GenericUnsafe] Startup Phase 1 duration: 986ms
06-09 01:11:42.208 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.GenericUnsafe] Startup Phase 2 duration: 927ms
06-09 01:11:42.218 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Starting: HockeyAppService
06-09 01:11:42.229 I ReactHockeyApp: HockeyApp - initializing configuration
06-09 01:11:42.229 I ReactNativeJS: [#ffffffff-S] [TRACE] [JS.HockeyApp] Ignoring check for updates - PUBLIC build
06-09 01:11:42.233 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Finish: HockeyAppService: 16ms
06-09 01:11:42.241 I React: Check for new app crashes
06-09 01:11:42.257 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Starting: CrashStatusStore
06-09 01:11:42.261 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.GenericUnsafe] RN Entry
06-09 01:11:42.273 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] Last app launch time: undefined
06-09 01:11:42.279 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] _getAppLaunchState:subscribe:fired:0
06-09 01:11:42.331 I ReactNativeJS: [#ffffffff-S] [TRACE] [JS.HockeyApp] Last launch crashed: false
06-09 01:11:42.332 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Finish: CrashStatusStore: 76ms
06-09 01:11:42.335 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] SkypeId missing in Storage
06-09 01:11:42.666 W ReactMethodWatchdog: Method RNCookieManagerAndroid.clearAll invocation took too long: 140ms
06-09 01:11:42.709 E CredentialsFetcher: Can't parse xml
06-09 01:11:42.709 E CredentialsFetcher: /data/user/0/com.skype.raider/files/shared.xml (No such file or directory)
06-09 01:11:42.709 E CredentialsFetcher: 	java.io.FileInputStream.open0(FileInputStream.java:-2)
06-09 01:11:42.709 E CredentialsFetcher: 	java.io.FileInputStream.open(FileInputStream.java:200)
06-09 01:11:42.709 E CredentialsFetcher: 	java.io.FileInputStream.<init>(FileInputStream.java:150)
06-09 01:11:42.709 E CredentialsFetcher: 	com.skype.credentials.CredentialsFetcher.a(SourceFile:44)
06-09 01:11:42.709 E CredentialsFetcher: 	com.skype.credentials.SkypeCredentialsFetcherModule.fetchUserInfo(SourceFile:46)
06-09 01:11:42.709 E CredentialsFetcher: 	java.lang.reflect.Method.invoke(Method.java:-2)
06-09 01:11:42.709 E CredentialsFetcher: 	com.facebook.react.bridge.q.a(SourceFile:366)
06-09 01:11:42.709 E CredentialsFetcher: 	com.facebook.react.bridge.JavaModuleWrapper$b.invoke(SourceFile:283)
06-09 01:11:42.709 E CredentialsFetcher: 	com.facebook.react.bridge.JavaModuleWrapper.invoke(SourceFile:176)
06-09 01:11:42.709 E CredentialsFetcher: 	com.facebook.react.bridge.queue.NativeRunnable.run(SourceFile:-2)
06-09 01:11:42.709 E CredentialsFetcher: 	android.os.Handler.handleCallback(Handler.java:789)
06-09 01:11:42.709 E CredentialsFetcher: 	android.os.Handler.dispatchMessage(Handler.java:98)
06-09 01:11:42.709 E CredentialsFetcher: 	com.facebook.react.bridge.queue.a.dispatchMessage(SourceFile:31)
06-09 01:11:42.709 E CredentialsFetcher: 	android.os.Looper.loop(Looper.java:164)
06-09 01:11:42.709 E CredentialsFetcher: 	com.facebook.react.bridge.queue.MessageQueueThreadImpl$3.run(SourceFile:194)
06-09 01:11:42.709 E CredentialsFetcher: 	java.lang.Thread.run(Thread.java:764)
06-09 01:11:42.794 I DeviceUtilities: DeviceUtilities: currentOrientation
06-09 01:11:42.901 W React: StatusBarModule: Ignored status bar change, current activity is null.
06-09 01:11:42.906 W React: StatusBarModule: Ignored status bar change, current activity is null.
06-09 01:11:42.912 W React: StatusBarModule: Ignored status bar change, current activity is null.
06-09 01:11:42.912 I DeviceUtilities: DeviceUtilities: statusBarHeight
06-09 01:11:42.958 W ReactNativeJS: [#ffffffff-u] [WARN] [JS.ResponsiveWidthStore] DeviceUtilities.currentOrientation failed: [pii<E...>] causeId: 1d67fbd2
06-09 01:11:42.961 W ReactNativeJS: [#ffffffff-u] [WARN] [JS.GenericUnsafe] SafeAreaStore statusBarHeight failed: [pii<E...>]
06-09 01:11:50.878 I RNSlimcore: Clearing old logs
06-09 01:11:50.887 I SkyLibManager[TERMINATED:null]: clearOldLogs found 0 potential log files
06-09 01:11:57.097 I UpgradeContext: releaseWakeLock taskId 1
06-09 01:11:57.101 I SimpleWakefulService: Release WAKE_LOCK for taskId: 1 with startId: 2
06-09 01:11:57.105 I SimpleWakefulService: Removing Stop message
06-09 01:11:57.106 I SimpleWakefulService: Service destroyed
06-09 07:28:08.089 W ReactHockeyApp: RNHockeyApp: Failed to get existing metadata
06-09 07:28:08.089 W ReactHockeyApp: /data/user/0/com.skype.raider/files/HockeyAppCrashMetadata.json (No such file or directory)
06-09 07:28:08.089 W ReactHockeyApp: 	java.io.FileInputStream.open0(FileInputStream.java:-2)
06-09 07:28:08.089 W ReactHockeyApp: 	java.io.FileInputStream.open(FileInputStream.java:200)
06-09 07:28:08.089 W ReactHockeyApp: 	java.io.FileInputStream.<init>(FileInputStream.java:150)
06-09 07:28:08.089 W ReactHockeyApp: 	android.app.ContextImpl.openFileInput(ContextImpl.java:520)
06-09 07:28:08.089 W ReactHockeyApp: 	android.content.ContextWrapper.openFileInput(ContextWrapper.java:200)
06-09 07:28:08.089 W ReactHockeyApp: 	com.skype.hockeyapp.SkypeCrashListener.f(SourceFile:139)
06-09 07:28:08.089 W ReactHockeyApp: 	com.skype.hockeyapp.SkypeCrashListener.<init>(SourceFile:48)
06-09 07:28:08.089 W ReactHockeyApp: 	com.skype.hockeyapp.SkypeCrashListener.a(SourceFile:43)
06-09 07:28:08.089 W ReactHockeyApp: 	com.skype.hockeyapp.SkypeCrashManager.a(SourceFile:37)
06-09 07:28:08.089 W ReactHockeyApp: 	com.skype4life.SkypeApplication.onCreate(SourceFile:1042)
06-09 07:28:08.089 W ReactHockeyApp: 	android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1125)
06-09 07:28:08.089 W ReactHockeyApp: 	android.app.ActivityThread.handleBindApplication(ActivityThread.java:6056)
06-09 07:28:08.089 W ReactHockeyApp: 	android.app.ActivityThread.-wrap1(null:0)
06-09 07:28:08.089 W ReactHockeyApp: 	android.app.ActivityThread$H.handleMessage(ActivityThread.java:1764)
06-09 07:28:08.089 W ReactHockeyApp: 	android.os.Handler.dispatchMessage(Handler.java:105)
06-09 07:28:08.089 W ReactHockeyApp: 	android.os.Looper.loop(Looper.java:164)
06-09 07:28:08.089 W ReactHockeyApp: 	android.app.ActivityThread.main(ActivityThread.java:6938)
06-09 07:28:08.089 W ReactHockeyApp: 	java.lang.reflect.Method.invoke(Method.java:-2)
06-09 07:28:08.089 W ReactHockeyApp: 	com.android.internal.os.Zygote$MethodAndArgsCaller.run(Zygote.java:327)
06-09 07:28:08.089 W ReactHockeyApp: 	com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1374)
06-09 07:28:08.125 I DumpUploader: Preparing check for new crash dumps
06-09 07:28:08.127 I DumpUploader: Started check for new crash dumps
06-09 07:28:08.128 I ReactApp: onCreate start
06-09 07:28:08.130 I DumpUploader: Marking dumps as known: 
06-09 07:28:08.135 I ReactApp: configureViewPools took 0ms
06-09 07:28:08.167 I ReactApp: configureOkHttp took 31ms
06-09 07:28:08.167 I ReactApp: configureStetho took 0ms
06-09 07:28:08.191 I ReactApp: configureYoga took 23ms
06-09 07:28:08.196 I ReactApp: CsiManager.onCreate took 4ms
06-09 07:28:08.298 I ReactApp: mReactNativeHost.getReactInstanceManager took 101ms
06-09 07:28:08.298 I ReactApp: onCreate complete in 392ms
06-09 07:28:08.298 I React: Creating react context.
06-09 07:28:08.304 I ActivationExperiment: loadFromDisk:{"experimentList":[],"schemaVersion":"v1","totalWakeAttempts":1,"wakeUpList":[{"reason":"Upgrade","status":"NextWakeUpScheduled","time":1528438083838},{"reason":"RtcWakeUp","status":"WakeUpPending","time":1528765683839}]}, timeTaken(2 ms)
06-09 07:28:08.313 I SkypeCameraViewManager: init
06-09 07:28:08.324 I ActivationExperiment: cancelPendingRtcWake
06-09 07:28:08.341 I GradientImagePackage: createViewManagers
06-09 07:28:08.348 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.ink.AdditiveSurfaceViewManager
06-09 07:28:08.356 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.ink.AdditiveSurfaceViewShadowNode
06-09 07:28:08.366 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.uimanager.h
06-09 07:28:08.379 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.text.g
06-09 07:28:08.400 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.textinput.i
06-09 07:28:08.427 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.art.c
06-09 07:28:08.429 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.art.b
06-09 07:28:08.432 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.art.a
06-09 07:28:08.435 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.progressbar.b
06-09 07:28:08.436 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.text.frescosupport.a
06-09 07:28:08.439 W ViewManagerPropertyUpdater: Could not find generated setter for class com.brentvatne.react.ReactVideoViewManager
06-09 07:28:08.443 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skpcamera.SkypeCameraViewManager
06-09 07:28:08.447 W ViewManagerPropertyUpdater: Could not find generated setter for class com.customkeyboard.CustomKeyboardViewManager
06-09 07:28:08.452 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.slimcore.video.RNCallingVideoViewManager
06-09 07:28:08.455 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.slimcore.video.RNCallingVideoViewLocalManager
06-09 07:28:08.459 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.react.mediapicker.MediaPickerViewManager
06-09 07:28:08.466 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.react.mediapicker.c
06-09 07:28:08.472 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.skypemessagetextinput.view.RNViewManager
06-09 07:28:08.476 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.skypemessagetextinput.view.c
06-09 07:28:08.477 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.reactnativesprites.SpriteViewManager
06-09 07:28:08.480 W ViewManagerPropertyUpdater: Could not find generated setter for class com.projectseptember.RNGL.GLCanvasManager
06-09 07:28:08.485 W ViewManagerPropertyUpdater: Could not find generated setter for class com.github.alinz.reactnativewebviewbridge.WebViewBridgeManager
06-09 07:28:08.492 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapCalloutManager
06-09 07:28:08.495 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapMarkerManager
06-09 07:28:08.499 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapPolylineManager
06-09 07:28:08.502 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapPolygonManager
06-09 07:28:08.510 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapCircleManager
06-09 07:28:08.513 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapManager
06-09 07:28:08.520 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapLiteManager
06-09 07:28:08.521 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapUrlTileManager
06-09 07:28:08.523 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.react.videofxp.VideoFXPViewManager
06-09 07:28:08.527 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.virtualmessageview.VirtualMessageViewControllerManager
06-09 07:28:08.529 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.react.clippedview.ClippedViewManager
06-09 07:28:08.531 W ViewManagerPropertyUpdater: Could not find generated setter for class com.BV.LinearGradient.LinearGradientManager
06-09 07:28:08.533 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.lottie.LottieAnimationViewManager
06-09 07:28:08.536 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.react.gradientimage.GradientImageViewManager
06-09 07:28:08.539 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.qrcode.QRCodeViewManager
06-09 07:28:08.542 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.camera.imagefilter.ImageFilterManager
06-09 07:28:08.770 W JavaModuleHelper: Could not find generated custom module provider
06-09 07:28:08.771 W React: There is no generated module helper for module: CallIntent using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.771 W React: There is no generated module helper for module: IncomingCallInteractionManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.771 W React: There is no generated module helper for module: RNStorage using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.772 W React: There is no generated module helper for module: CustomKeyboard using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.772 W React: There is no generated module helper for module: SplashScreenNotifier using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.772 W React: There is no generated module helper for module: RNViewConfig using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.772 W React: There is no generated module helper for module: FingerprintingLib using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.773 W React: There is no generated module helper for module: RNReload using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.773 W React: There is no generated module helper for module: VideoFXP using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.773 W React: There is no generated module helper for module: Adjust using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.773 W React: There is no generated module helper for module: SkypeCamera using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.773 W React: There is no generated module helper for module: AirMapModule using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.773 W React: There is no generated module helper for module: ContextMenuAndroid using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.774 W React: There is no generated module helper for module: DeviceUtilities using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.774 W React: There is no generated module helper for module: RNGLContext using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.774 W React: There is no generated module helper for module: ExternalBrowser using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.774 W React: There is no generated module helper for module: TokenShareModule using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.774 W React: There is no generated module helper for module: UrlUtil using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.774 W React: There is no generated module helper for module: FileEncryptionNative using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.775 W React: There is no generated module helper for module: EnvironmentInfo using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.775 W React: There is no generated module helper for module: RNDocumentPicker using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.775 W React: There is no generated module helper for module: AndroidSmsManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.775 W React: There is no generated module helper for module: MediaPicker using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.775 W React: There is no generated module helper for module: PermissionsManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.775 W React: There is no generated module helper for module: SoundPlayer using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.776 W React: There is no generated module helper for module: RNCookieManagerAndroid using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.776 W React: There is no generated module helper for module: NativeEntropy using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.776 W React: There is no generated module helper for module: AudioManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.776 W React: There is no generated module helper for module: FrescoModule using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.776 W React: There is no generated module helper for module: RNAppUpgrade using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.777 W React: There is no generated module helper for module: AndroidBadges using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.777 W React: There is no generated module helper for module: RNSlimcore using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.777 W React: There is no generated module helper for module: RNUrlRequest using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.777 W React: There is no generated module helper for module: ZipUtil using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.777 W React: There is no generated module helper for module: PlatformConstants using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.777 W React: There is no generated module helper for module: ShareToApp using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.778 W React: There is no generated module helper for module: RNGraphicsContext using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.778 W React: There is no generated module helper for module: SourceCode using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.778 W React: There is no generated module helper for module: SoundRecorder using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.778 W React: There is no generated module helper for module: ImagePickerManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.778 W React: There is no generated module helper for module: RNBackgroundTimer using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.778 W React: There is no generated module helper for module: RNCommandInvoker using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.779 W React: There is no generated module helper for module: ImageResizerAndroid using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.779 W React: There is no generated module helper for module: RNManualFileCache using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.779 W React: There is no generated module helper for module: CortanaSignals using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.779 W React: There is no generated module helper for module: RNPushAndroid using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.779 W React: There is no generated module helper for module: ShareSheet using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.779 W React: There is no generated module helper for module: RNSkypeCredentialsFetcher using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.780 W React: There is no generated module helper for module: RNKeychainManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.780 W React: There is no generated module helper for module: ExtendedAppState using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.780 W React: There is no generated module helper for module: CampaignReceiver using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.780 W React: There is no generated module helper for module: Contacts using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.781 W React: There is no generated module helper for module: SKPSkypeMessageTextInputModule using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.781 W React: There is no generated module helper for module: RNHockeyApp using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.781 W React: There is no generated module helper for module: DeviceSettings using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.781 W React: There is no generated module helper for module: AdvertisementUtilities using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.781 W React: There is no generated module helper for module: RNNetworkInfo using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.782 W React: There is no generated module helper for module: StyleTransfer using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.782 W React: There is no generated module helper for module: SnapshotManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.782 W React: There is no generated module helper for module: DeviceInfo using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.782 W React: There is no generated module helper for module: ClientLogging using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.782 W React: There is no generated module helper for module: RNBackgroundExecution using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.783 W React: There is no generated module helper for module: TimeZoneManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.783 W React: There is no generated module helper for module: CallMonitor using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.783 W React: There is no generated module helper for module: AssetReader using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.784 W React: There is no generated module helper for module: RNGeocoder using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.784 W React: There is no generated module helper for module: FileTracker using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 07:28:08.827 I SmsHandlingContext: init()
06-09 07:28:08.829 I SkypeCameraModule: SkypeCameraModule initialize
06-09 07:28:08.832 I AudioManagerModule: initialize (causeId 54be6736)
06-09 07:28:08.833 I AudioManagerModule: AudioManagerModule.initialize took 1ms
06-09 07:28:08.834 I AudioOptions: initialize (causeId 54be6736)
06-09 07:28:08.835 I WiredHeadsetReceiver: Registered receiver
06-09 07:28:08.836 I WiredHeadsetReceiver: addListener (causeId: 54be6736)
06-09 07:28:08.836 I AudioOptions: WiredHeadsetReceiver.headsetStateChanged UNPLUGGED (causeId 54be6736)
06-09 07:28:08.837 I BluetoothReceiver: Received sticky intent android.media.ACTION_SCO_AUDIO_STATE_UPDATED
06-09 07:28:08.837 I BluetoothReceiver: Registered receiver
06-09 07:28:08.837 I BluetoothReceiver: loadAlreadyConnectedDevices (causeId: 54be6736)
06-09 07:28:08.838 I BluetoothReceiver: onReceive action android.media.ACTION_SCO_AUDIO_STATE_UPDATED (causeId a3ef67e0)
06-09 07:28:08.838 I BluetoothReceiver: handleScoAudioStateChange prevState: -1 state: 0 (causeId: a3ef67e0)
06-09 07:28:08.838 I BluetoothReceiver: scoDisconnected
06-09 07:28:08.841 W ReactApp: registerMemoryTrimmable current size: 0
06-09 07:28:08.841 W ReactApp: registerMemoryTrimmable current size: 1
06-09 07:28:08.841 I BluetoothReceiver: addListener (causeId: 54be6736)
06-09 07:28:08.842 I BluetoothReceiver: createServiceListener (causeId: 54be6736)
06-09 07:28:08.844 I BluetoothReceiver: onReceive action android.media.ACTION_SCO_AUDIO_STATE_UPDATED (causeId f3875884)
06-09 07:28:08.844 I BluetoothReceiver: handleScoAudioStateChange prevState: -1 state: 0 (causeId: f3875884)
06-09 07:28:08.844 I BluetoothReceiver: scoDisconnected
06-09 07:28:08.844 I AudioOptions: BluetoothReceiver.scoDisconnected (causeId f3875884)
06-09 07:28:08.845 I BluetoothReceiver: onReceive action android.media.SCO_AUDIO_STATE_CHANGED (causeId 29281b82)
06-09 07:28:08.845 I BluetoothReceiver: handleScoAudioStateChange prevState: 0 state: 0 (causeId: 29281b82)
06-09 07:28:08.845 I BluetoothReceiver: scoDisconnected
06-09 07:28:08.845 I AudioOptions: BluetoothReceiver.scoDisconnected (causeId 29281b82)
06-09 07:28:08.853 I ModernAudioDeviceMonitor: addListener (causeId: 54be6736)
06-09 07:28:08.853 I AudioOptions: ModernAudioDeviceMonitor.availableAudioDeviceTypesChanged headphones: false usb: false (causeId 54be6736)
06-09 07:28:08.857 I ModernAudioDeviceMonitor: initialization headphones: false, usb: false, devices: [[1:TYPE_BUILTIN_EARPIECE], [2:TYPE_BUILTIN_SPEAKER], [6:TYPE_BUILTIN_MIC], [8:TYPE_TELEPHONY]] (causeId: 4f286960)
06-09 07:28:08.882 I TokenShareModule: getAccounts() called, returned with list size 0
06-09 07:28:08.898 I ModernAudioDeviceMonitor: onAudioDevicesAdded headphones: false, usb: false, devices: [[1:TYPE_BUILTIN_EARPIECE], [2:TYPE_BUILTIN_SPEAKER], [6:TYPE_BUILTIN_MIC], [8:TYPE_TELEPHONY]] (causeId: f7247992)
06-09 07:28:08.900 I TelephoneStateListener: Registering phone state listener (causeId 54be6736)
06-09 07:28:08.900 I ModernAudioDeviceMonitor: onAudioDevicesAdded headphones: false, usb: false, devices: [[1:TYPE_BUILTIN_EARPIECE], [2:TYPE_BUILTIN_SPEAKER], [6:TYPE_BUILTIN_MIC], [8:TYPE_TELEPHONY]] (causeId: e11ea81e)
06-09 07:28:08.901 I AudioManagerModule: Sending output changed event to EARPIECE (causeId 54be6736)
06-09 07:28:08.911 I AudioManagerModule: calcSettingsAndUpdate: Skipping - not initialized (causeId: 54be6736)
06-09 07:28:08.912 I AudioManagerModule: TelephoneStateListener.init took 15ms
06-09 07:28:08.918 I TelephoneStateListener: Forcing update of phone state (causeId f3875884)
06-09 07:28:08.923 I AudioManagerModule: mergedSettingForSettings default output route computed as SPEAKER (causeId: f3875884)
06-09 07:28:08.923 I AudioManagerModule: calcSettingsAndUpdate: current: (stream=USE_DEFAULT_STREAM_TYPE, mode=MODE_INVALID, focus=DOES NOT WANT, route=EARPIECE), merged: (stream=USE_DEFAULT_STREAM_TYPE, mode=MODE_NORMAL, focus=DOES NOT WANT, route=SPEAKER), modes: [], background: false, focusState: Unknown, inPhoneCall: false (causeId f3875884)
06-09 07:28:08.924 I AudioManagerModule: Setting audio mode MODE_INVALID -> MODE_NORMAL (causeId f3875884)
06-09 07:28:08.932 I AudioManagerModule: Setting audio route EARPIECE -> SPEAKER (causeId f3875884)
06-09 07:28:08.932 I AudioOptions: routeAudioOutput SPEAKER (causeId f3875884)
06-09 07:28:08.933 I AudioOptions: intRouteAudioOutput SPEAKER userAction=true (causeId f3875884)
06-09 07:28:08.934 I TelephoneStateListener: Forcing update of phone state (causeId 29281b82)
06-09 07:28:08.935 I AudioManagerModule: Sending output changed event to SPEAKER (causeId f3875884)
06-09 07:28:08.936 I AudioManagerModule: mergedSettingForSettings default output route computed as SPEAKER (causeId: 29281b82)
06-09 07:28:08.937 I AudioManagerModule: calcSettingsAndUpdate: current: (stream=USE_DEFAULT_STREAM_TYPE, mode=MODE_NORMAL, focus=DOES NOT WANT, route=SPEAKER), merged: (stream=USE_DEFAULT_STREAM_TYPE, mode=MODE_NORMAL, focus=DOES NOT WANT, route=SPEAKER), modes: [], background: false, focusState: Unknown, inPhoneCall: false (causeId 29281b82)
06-09 07:28:08.937 I TelephoneStateListener: Forcing update of phone state (causeId 54be6736)
06-09 07:28:08.938 I AudioOptions: Active audio output destination is SPEAKER (causeId f3875884)
06-09 07:28:08.939 I AudioManagerModule: mergedSettingForSettings default output route computed as SPEAKER (causeId: 54be6736)
06-09 07:28:08.939 I AudioManagerModule: calcSettingsAndUpdate: current: (stream=USE_DEFAULT_STREAM_TYPE, mode=MODE_NORMAL, focus=DOES NOT WANT, route=SPEAKER), merged: (stream=USE_DEFAULT_STREAM_TYPE, mode=MODE_NORMAL, focus=DOES NOT WANT, route=SPEAKER), modes: [], background: false, focusState: Unknown, inPhoneCall: false (causeId 54be6736)
06-09 07:28:08.941 I TelephoneStateListener: onCallStateChanged 0 (causeId 3c5bd9a3)
06-09 07:28:09.723 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'StaticTask.OnAppUpdated'
06-09 07:28:09.726 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'StaticTask.OnAppUpdatedRetry'
06-09 07:28:09.776 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'SignInOnUserSessionConnected'
06-09 07:28:09.776 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'SignInOnUserSessionConnectedRetry'
06-09 07:28:09.777 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'SignInOnDefaultMSAConnected'
06-09 07:28:09.777 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'SignInOnDefaultMSAConnectedRetry'
06-09 07:28:09.779 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'OnMaintenanceWindowStart'
06-09 07:28:09.780 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'OnMaintenanceWindowStartRetry'
06-09 07:28:09.811 I RNAppUpgrade: Getting app launch attribution state = false
06-09 07:28:09.812 I RNAppUpgrade: hasOldSessionPreferences:false
06-09 07:28:09.819 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] Preparing to handle App Upgrade Event
06-09 07:28:09.820 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] Preparing to handle Rtc Wake Event
06-09 07:28:09.820 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] _setUpAppLaunchStateChangeListener
06-09 07:28:09.822 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] _setUpNoticationClickListener
06-09 07:28:09.824 I RNAppUpgrade: initialize
06-09 07:28:09.825 I UpgradeContext: acquireWakeLock taskId 1
06-09 07:28:09.830 I SimpleWakefulService: Service created
06-09 07:28:09.830 I SimpleWakefulService: Acquire WAKE_LOCK for taskId: 1 with startId: 1
06-09 07:28:09.834 I RNAppUpgrade: processPendingIntents
06-09 07:28:09.835 I RNAppUpgrade: processPendingIntents:delayedIntentQueue size(0)
06-09 07:28:09.835 I RNAppUpgrade: initialize
06-09 07:28:09.939 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Locale initialized to [en_CA]
06-09 07:28:09.940 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Country code is [CA]
06-09 07:28:09.956 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Device Id: fkgXjGl17eI
06-09 07:28:09.956 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Device Manufacturer: samsung
06-09 07:28:09.957 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Device Model: SM-G955W
06-09 07:28:09.958 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Device OS version: 8.0.0
06-09 07:28:09.961 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] App version: 8.23.0.10
06-09 07:28:09.962 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] App activation state: Background
06-09 07:28:09.973 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.GenericUnsafe] Startup Phase 1 duration: 960ms
06-09 07:28:09.984 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.GenericUnsafe] Startup Phase 2 duration: 923ms
06-09 07:28:09.996 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Starting: HockeyAppService
06-09 07:28:10.006 I ReactHockeyApp: HockeyApp - initializing configuration
06-09 07:28:10.006 I ReactNativeJS: [#ffffffff-S] [TRACE] [JS.HockeyApp] Ignoring check for updates - PUBLIC build
06-09 07:28:10.009 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Finish: HockeyAppService: 14ms
06-09 07:28:10.016 I React: Check for new app crashes
06-09 07:28:10.030 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Starting: CrashStatusStore
06-09 07:28:10.033 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.GenericUnsafe] RN Entry
06-09 07:28:10.044 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] Last app launch time: undefined
06-09 07:28:10.051 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] _getAppLaunchState:subscribe:fired:0
06-09 07:28:10.100 I ReactNativeJS: [#ffffffff-S] [TRACE] [JS.HockeyApp] Last launch crashed: false
06-09 07:28:10.102 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Finish: CrashStatusStore: 72ms
06-09 07:28:10.107 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] SkypeId missing in Storage
06-09 07:28:10.405 E CredentialsFetcher: Can't parse xml
06-09 07:28:10.405 E CredentialsFetcher: /data/user/0/com.skype.raider/files/shared.xml (No such file or directory)
06-09 07:28:10.405 E CredentialsFetcher: 	java.io.FileInputStream.open0(FileInputStream.java:-2)
06-09 07:28:10.405 E CredentialsFetcher: 	java.io.FileInputStream.open(FileInputStream.java:200)
06-09 07:28:10.405 E CredentialsFetcher: 	java.io.FileInputStream.<init>(FileInputStream.java:150)
06-09 07:28:10.405 E CredentialsFetcher: 	com.skype.credentials.CredentialsFetcher.a(SourceFile:44)
06-09 07:28:10.405 E CredentialsFetcher: 	com.skype.credentials.SkypeCredentialsFetcherModule.fetchUserInfo(SourceFile:46)
06-09 07:28:10.405 E CredentialsFetcher: 	java.lang.reflect.Method.invoke(Method.java:-2)
06-09 07:28:10.405 E CredentialsFetcher: 	com.facebook.react.bridge.q.a(SourceFile:366)
06-09 07:28:10.405 E CredentialsFetcher: 	com.facebook.react.bridge.JavaModuleWrapper$b.invoke(SourceFile:283)
06-09 07:28:10.405 E CredentialsFetcher: 	com.facebook.react.bridge.JavaModuleWrapper.invoke(SourceFile:176)
06-09 07:28:10.405 E CredentialsFetcher: 	com.facebook.react.bridge.queue.NativeRunnable.run(SourceFile:-2)
06-09 07:28:10.405 E CredentialsFetcher: 	android.os.Handler.handleCallback(Handler.java:789)
06-09 07:28:10.405 E CredentialsFetcher: 	android.os.Handler.dispatchMessage(Handler.java:98)
06-09 07:28:10.405 E CredentialsFetcher: 	com.facebook.react.bridge.queue.a.dispatchMessage(SourceFile:31)
06-09 07:28:10.405 E CredentialsFetcher: 	android.os.Looper.loop(Looper.java:164)
06-09 07:28:10.405 E CredentialsFetcher: 	com.facebook.react.bridge.queue.MessageQueueThreadImpl$3.run(SourceFile:194)
06-09 07:28:10.405 E CredentialsFetcher: 	java.lang.Thread.run(Thread.java:764)
06-09 07:28:10.493 I DeviceUtilities: DeviceUtilities: currentOrientation
06-09 07:28:10.600 W React: StatusBarModule: Ignored status bar change, current activity is null.
06-09 07:28:10.605 W React: StatusBarModule: Ignored status bar change, current activity is null.
06-09 07:28:10.610 W React: StatusBarModule: Ignored status bar change, current activity is null.
06-09 07:28:10.610 I DeviceUtilities: DeviceUtilities: statusBarHeight
06-09 07:28:10.653 W ReactNativeJS: [#ffffffff-u] [WARN] [JS.ResponsiveWidthStore] DeviceUtilities.currentOrientation failed: [pii<E...>] causeId: e099bac7
06-09 07:28:10.657 W ReactNativeJS: [#ffffffff-u] [WARN] [JS.GenericUnsafe] SafeAreaStore statusBarHeight failed: [pii<E...>]
06-09 07:28:18.741 I RNSlimcore: Clearing old logs
06-09 07:28:18.746 I SkyLibManager[TERMINATED:null]: clearOldLogs found 0 potential log files
06-09 07:28:24.875 I UpgradeContext: releaseWakeLock taskId 1
06-09 07:28:24.884 I SimpleWakefulService: Release WAKE_LOCK for taskId: 1 with startId: 2
06-09 07:28:24.891 I SimpleWakefulService: Removing Stop message
06-09 07:28:24.904 I SimpleWakefulService: Service destroyed
06-09 09:47:12.530 W ReactHockeyApp: RNHockeyApp: Failed to get existing metadata
06-09 09:47:12.530 W ReactHockeyApp: /data/user/0/com.skype.raider/files/HockeyAppCrashMetadata.json (No such file or directory)
06-09 09:47:12.530 W ReactHockeyApp: 	java.io.FileInputStream.open0(FileInputStream.java:-2)
06-09 09:47:12.530 W ReactHockeyApp: 	java.io.FileInputStream.open(FileInputStream.java:200)
06-09 09:47:12.530 W ReactHockeyApp: 	java.io.FileInputStream.<init>(FileInputStream.java:150)
06-09 09:47:12.530 W ReactHockeyApp: 	android.app.ContextImpl.openFileInput(ContextImpl.java:520)
06-09 09:47:12.530 W ReactHockeyApp: 	android.content.ContextWrapper.openFileInput(ContextWrapper.java:200)
06-09 09:47:12.530 W ReactHockeyApp: 	com.skype.hockeyapp.SkypeCrashListener.f(SourceFile:139)
06-09 09:47:12.530 W ReactHockeyApp: 	com.skype.hockeyapp.SkypeCrashListener.<init>(SourceFile:48)
06-09 09:47:12.530 W ReactHockeyApp: 	com.skype.hockeyapp.SkypeCrashListener.a(SourceFile:43)
06-09 09:47:12.530 W ReactHockeyApp: 	com.skype.hockeyapp.SkypeCrashManager.a(SourceFile:37)
06-09 09:47:12.530 W ReactHockeyApp: 	com.skype4life.SkypeApplication.onCreate(SourceFile:1042)
06-09 09:47:12.530 W ReactHockeyApp: 	android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1125)
06-09 09:47:12.530 W ReactHockeyApp: 	android.app.ActivityThread.handleBindApplication(ActivityThread.java:6056)
06-09 09:47:12.530 W ReactHockeyApp: 	android.app.ActivityThread.-wrap1(null:0)
06-09 09:47:12.530 W ReactHockeyApp: 	android.app.ActivityThread$H.handleMessage(ActivityThread.java:1764)
06-09 09:47:12.530 W ReactHockeyApp: 	android.os.Handler.dispatchMessage(Handler.java:105)
06-09 09:47:12.530 W ReactHockeyApp: 	android.os.Looper.loop(Looper.java:164)
06-09 09:47:12.530 W ReactHockeyApp: 	android.app.ActivityThread.main(ActivityThread.java:6938)
06-09 09:47:12.530 W ReactHockeyApp: 	java.lang.reflect.Method.invoke(Method.java:-2)
06-09 09:47:12.530 W ReactHockeyApp: 	com.android.internal.os.Zygote$MethodAndArgsCaller.run(Zygote.java:327)
06-09 09:47:12.530 W ReactHockeyApp: 	com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1374)
06-09 09:47:12.557 I DumpUploader: Preparing check for new crash dumps
06-09 09:47:12.569 I ReactApp: onCreate start
06-09 09:47:12.582 I DumpUploader: Started check for new crash dumps
06-09 09:47:12.595 I DumpUploader: Marking dumps as known: 
06-09 09:47:12.595 I ReactApp: configureViewPools took 0ms
06-09 09:47:12.644 I ReactApp: configureOkHttp took 46ms
06-09 09:47:12.645 I ReactApp: configureStetho took 0ms
06-09 09:47:12.658 I ReactApp: configureYoga took 13ms
06-09 09:47:12.664 I ReactApp: CsiManager.onCreate took 5ms
06-09 09:47:12.750 I ReactApp: mReactNativeHost.getReactInstanceManager took 84ms
06-09 09:47:12.750 I ReactApp: onCreate complete in 373ms
06-09 09:47:12.750 I React: Creating react context.
06-09 09:47:12.757 I ActivationExperiment: loadFromDisk:{"experimentList":[],"schemaVersion":"v1","totalWakeAttempts":1,"wakeUpList":[{"reason":"Upgrade","status":"NextWakeUpScheduled","time":1528438083838},{"reason":"RtcWakeUp","status":"WakeUpPending","time":1528765683839}]}, timeTaken(4 ms)
06-09 09:47:12.766 I SkypeCameraViewManager: init
06-09 09:47:12.781 I ActivationExperiment: cancelPendingRtcWake
06-09 09:47:12.787 I GradientImagePackage: createViewManagers
06-09 09:47:12.793 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.ink.AdditiveSurfaceViewManager
06-09 09:47:12.801 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.ink.AdditiveSurfaceViewShadowNode
06-09 09:47:12.814 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.uimanager.h
06-09 09:47:12.833 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.text.g
06-09 09:47:12.850 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.textinput.i
06-09 09:47:12.879 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.art.c
06-09 09:47:12.881 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.art.b
06-09 09:47:12.884 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.art.a
06-09 09:47:12.886 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.progressbar.b
06-09 09:47:12.891 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.text.frescosupport.a
06-09 09:47:12.894 W ViewManagerPropertyUpdater: Could not find generated setter for class com.brentvatne.react.ReactVideoViewManager
06-09 09:47:12.901 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skpcamera.SkypeCameraViewManager
06-09 09:47:12.908 W ViewManagerPropertyUpdater: Could not find generated setter for class com.customkeyboard.CustomKeyboardViewManager
06-09 09:47:12.913 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.slimcore.video.RNCallingVideoViewManager
06-09 09:47:12.916 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.slimcore.video.RNCallingVideoViewLocalManager
06-09 09:47:12.920 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.react.mediapicker.MediaPickerViewManager
06-09 09:47:12.928 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.react.mediapicker.c
06-09 09:47:12.934 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.skypemessagetextinput.view.RNViewManager
06-09 09:47:12.938 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.skypemessagetextinput.view.c
06-09 09:47:12.945 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.reactnativesprites.SpriteViewManager
06-09 09:47:12.951 W ViewManagerPropertyUpdater: Could not find generated setter for class com.projectseptember.RNGL.GLCanvasManager
06-09 09:47:12.959 W ViewManagerPropertyUpdater: Could not find generated setter for class com.github.alinz.reactnativewebviewbridge.WebViewBridgeManager
06-09 09:47:12.966 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapCalloutManager
06-09 09:47:12.968 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapMarkerManager
06-09 09:47:12.983 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapPolylineManager
06-09 09:47:12.988 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapPolygonManager
06-09 09:47:12.996 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapCircleManager
06-09 09:47:13.002 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapManager
06-09 09:47:13.027 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapLiteManager
06-09 09:47:13.028 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapUrlTileManager
06-09 09:47:13.031 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.react.videofxp.VideoFXPViewManager
06-09 09:47:13.048 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.virtualmessageview.VirtualMessageViewControllerManager
06-09 09:47:13.049 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.react.clippedview.ClippedViewManager
06-09 09:47:13.051 W ViewManagerPropertyUpdater: Could not find generated setter for class com.BV.LinearGradient.LinearGradientManager
06-09 09:47:13.054 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.lottie.LottieAnimationViewManager
06-09 09:47:13.057 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.react.gradientimage.GradientImageViewManager
06-09 09:47:13.060 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.qrcode.QRCodeViewManager
06-09 09:47:13.072 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.camera.imagefilter.ImageFilterManager
06-09 09:47:13.417 W JavaModuleHelper: Could not find generated custom module provider
06-09 09:47:13.418 W React: There is no generated module helper for module: RNAppUpgrade using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.418 W React: There is no generated module helper for module: Contacts using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.419 W React: There is no generated module helper for module: RNBackgroundExecution using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.419 W React: There is no generated module helper for module: CallIntent using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.419 W React: There is no generated module helper for module: DeviceSettings using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.419 W React: There is no generated module helper for module: RNSkypeCredentialsFetcher using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.419 W React: There is no generated module helper for module: RNKeychainManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.420 W React: There is no generated module helper for module: FrescoModule using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.420 W React: There is no generated module helper for module: CallMonitor using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.421 W React: There is no generated module helper for module: ShareSheet using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.421 W React: There is no generated module helper for module: RNGraphicsContext using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.421 W React: There is no generated module helper for module: StyleTransfer using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.421 W React: There is no generated module helper for module: MediaPicker using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.422 W React: There is no generated module helper for module: DeviceInfo using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.422 W React: There is no generated module helper for module: VideoFXP using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.423 W React: There is no generated module helper for module: SourceCode using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.423 W React: There is no generated module helper for module: SoundRecorder using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.424 W React: There is no generated module helper for module: RNUrlRequest using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.426 W React: There is no generated module helper for module: RNSlimcore using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.427 W React: There is no generated module helper for module: FingerprintingLib using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.427 W React: There is no generated module helper for module: AdvertisementUtilities using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.428 W React: There is no generated module helper for module: ZipUtil using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.428 W React: There is no generated module helper for module: AirMapModule using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.428 W React: There is no generated module helper for module: ExternalBrowser using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.428 W React: There is no generated module helper for module: PlatformConstants using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.429 W React: There is no generated module helper for module: RNStorage using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.429 W React: There is no generated module helper for module: RNHockeyApp using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.430 W React: There is no generated module helper for module: RNCookieManagerAndroid using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.430 W React: There is no generated module helper for module: SnapshotManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.430 W React: There is no generated module helper for module: AndroidBadges using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.431 W React: There is no generated module helper for module: ShareToApp using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.431 W React: There is no generated module helper for module: SoundPlayer using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.432 W React: There is no generated module helper for module: CortanaSignals using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.432 W React: There is no generated module helper for module: RNCommandInvoker using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.432 W React: There is no generated module helper for module: TokenShareModule using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.432 W React: There is no generated module helper for module: SkypeCamera using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.433 W React: There is no generated module helper for module: FileEncryptionNative using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.433 W React: There is no generated module helper for module: NativeEntropy using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.434 W React: There is no generated module helper for module: CustomKeyboard using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.434 W React: There is no generated module helper for module: AudioManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.434 W React: There is no generated module helper for module: RNManualFileCache using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.434 W React: There is no generated module helper for module: EnvironmentInfo using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.435 W React: There is no generated module helper for module: TimeZoneManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.435 W React: There is no generated module helper for module: RNNetworkInfo using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.435 W React: There is no generated module helper for module: PermissionsManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.435 W React: There is no generated module helper for module: ImageResizerAndroid using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.435 W React: There is no generated module helper for module: DeviceUtilities using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.435 W React: There is no generated module helper for module: AndroidSmsManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.436 W React: There is no generated module helper for module: RNGLContext using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.436 W React: There is no generated module helper for module: ContextMenuAndroid using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.436 W React: There is no generated module helper for module: SKPSkypeMessageTextInputModule using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.436 W React: There is no generated module helper for module: RNViewConfig using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.436 W React: There is no generated module helper for module: SplashScreenNotifier using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.436 W React: There is no generated module helper for module: RNBackgroundTimer using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.437 W React: There is no generated module helper for module: RNPushAndroid using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.438 W React: There is no generated module helper for module: ExtendedAppState using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.438 W React: There is no generated module helper for module: Adjust using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.438 W React: There is no generated module helper for module: ClientLogging using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.438 W React: There is no generated module helper for module: FileTracker using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.439 W React: There is no generated module helper for module: RNDocumentPicker using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.440 W React: There is no generated module helper for module: IncomingCallInteractionManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.441 W React: There is no generated module helper for module: RNReload using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.441 W React: There is no generated module helper for module: ImagePickerManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.442 W React: There is no generated module helper for module: RNGeocoder using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.442 W React: There is no generated module helper for module: AssetReader using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.443 W React: There is no generated module helper for module: UrlUtil using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.443 W React: There is no generated module helper for module: CampaignReceiver using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 09:47:13.503 I SmsHandlingContext: init()
06-09 09:47:13.509 W ReactApp: registerMemoryTrimmable current size: 0
06-09 09:47:13.509 W ReactApp: registerMemoryTrimmable current size: 1
06-09 09:47:13.523 I SkypeCameraModule: SkypeCameraModule initialize
06-09 09:47:13.524 I AudioManagerModule: initialize (causeId f29551bf)
06-09 09:47:13.525 I AudioManagerModule: AudioManagerModule.initialize took 1ms
06-09 09:47:13.526 I AudioOptions: initialize (causeId f29551bf)
06-09 09:47:13.528 I WiredHeadsetReceiver: Registered receiver
06-09 09:47:13.529 I WiredHeadsetReceiver: addListener (causeId: f29551bf)
06-09 09:47:13.530 I AudioOptions: WiredHeadsetReceiver.headsetStateChanged UNPLUGGED (causeId f29551bf)
06-09 09:47:13.530 I BluetoothReceiver: Received sticky intent android.media.ACTION_SCO_AUDIO_STATE_UPDATED
06-09 09:47:13.533 I BluetoothReceiver: Registered receiver
06-09 09:47:13.533 I BluetoothReceiver: loadAlreadyConnectedDevices (causeId: f29551bf)
06-09 09:47:13.534 I BluetoothReceiver: onReceive action android.media.ACTION_SCO_AUDIO_STATE_UPDATED (causeId 2c662ca4)
06-09 09:47:13.535 I BluetoothReceiver: handleScoAudioStateChange prevState: -1 state: 0 (causeId: 2c662ca4)
06-09 09:47:13.535 I BluetoothReceiver: scoDisconnected
06-09 09:47:13.535 I BluetoothReceiver: onReceive action android.media.ACTION_SCO_AUDIO_STATE_UPDATED (causeId edd3a5)
06-09 09:47:13.535 I BluetoothReceiver: handleScoAudioStateChange prevState: -1 state: 0 (causeId: edd3a5)
06-09 09:47:13.536 I BluetoothReceiver: scoDisconnected
06-09 09:47:13.536 I BluetoothReceiver: onReceive action android.media.SCO_AUDIO_STATE_CHANGED (causeId cc6122af)
06-09 09:47:13.536 I BluetoothReceiver: handleScoAudioStateChange prevState: 0 state: 0 (causeId: cc6122af)
06-09 09:47:13.536 I BluetoothReceiver: createServiceListener (causeId: f29551bf)
06-09 09:47:13.536 I BluetoothReceiver: scoDisconnected
06-09 09:47:13.537 I BluetoothReceiver: addListener (causeId: f29551bf)
06-09 09:47:13.559 I ModernAudioDeviceMonitor: addListener (causeId: f29551bf)
06-09 09:47:13.559 I AudioOptions: ModernAudioDeviceMonitor.availableAudioDeviceTypesChanged headphones: false usb: false (causeId f29551bf)
06-09 09:47:13.564 I ModernAudioDeviceMonitor: initialization headphones: false, usb: false, devices: [[1:TYPE_BUILTIN_EARPIECE], [2:TYPE_BUILTIN_SPEAKER], [6:TYPE_BUILTIN_MIC], [8:TYPE_TELEPHONY]] (causeId: 9874386b)
06-09 09:47:13.565 I TelephoneStateListener: Registering phone state listener (causeId f29551bf)
06-09 09:47:13.566 I ModernAudioDeviceMonitor: onAudioDevicesAdded headphones: false, usb: false, devices: [[1:TYPE_BUILTIN_EARPIECE], [2:TYPE_BUILTIN_SPEAKER], [6:TYPE_BUILTIN_MIC], [8:TYPE_TELEPHONY]] (causeId: ac677e8d)
06-09 09:47:13.568 I AudioManagerModule: Sending output changed event to EARPIECE (causeId f29551bf)
06-09 09:47:13.573 I AudioManagerModule: calcSettingsAndUpdate: Skipping - not initialized (causeId: f29551bf)
06-09 09:47:13.576 I AudioManagerModule: calcSettingsAndUpdate: Skipping - not initialized (causeId: f29551bf)
06-09 09:47:13.601 I AudioManagerModule: TelephoneStateListener.init took 28ms
06-09 09:47:13.603 I TelephoneStateListener: onCallStateChanged 0 (causeId a4e5d792)
06-09 09:47:13.627 I TokenShareModule: getAccounts() called, returned with list size 0
06-09 09:47:14.866 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'StaticTask.OnAppUpdated'
06-09 09:47:14.869 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'StaticTask.OnAppUpdatedRetry'
06-09 09:47:14.924 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'SignInOnUserSessionConnected'
06-09 09:47:14.925 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'SignInOnUserSessionConnectedRetry'
06-09 09:47:14.925 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'SignInOnDefaultMSAConnected'
06-09 09:47:14.926 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'SignInOnDefaultMSAConnectedRetry'
06-09 09:47:14.930 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'OnMaintenanceWindowStart'
06-09 09:47:14.931 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'OnMaintenanceWindowStartRetry'
06-09 09:47:14.961 I RNAppUpgrade: Getting app launch attribution state = false
06-09 09:47:14.965 I RNAppUpgrade: hasOldSessionPreferences:false
06-09 09:47:14.971 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] Preparing to handle App Upgrade Event
06-09 09:47:14.972 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] Preparing to handle Rtc Wake Event
06-09 09:47:14.973 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] _setUpAppLaunchStateChangeListener
06-09 09:47:14.975 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] _setUpNoticationClickListener
06-09 09:47:14.980 I RNAppUpgrade: initialize
06-09 09:47:14.980 I UpgradeContext: acquireWakeLock taskId 1
06-09 09:47:14.985 I SimpleWakefulService: Service created
06-09 09:47:14.985 I SimpleWakefulService: Acquire WAKE_LOCK for taskId: 1 with startId: 1
06-09 09:47:14.987 I RNAppUpgrade: processPendingIntents
06-09 09:47:14.987 I RNAppUpgrade: processPendingIntents:delayedIntentQueue size(0)
06-09 09:47:14.988 I RNAppUpgrade: initialize
06-09 09:47:15.128 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Locale initialized to [en_CA]
06-09 09:47:15.129 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Country code is [CA]
06-09 09:47:15.146 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Device Id: fkgXjGl17eI
06-09 09:47:15.147 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Device Manufacturer: samsung
06-09 09:47:15.148 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Device Model: SM-G955W
06-09 09:47:15.149 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Device OS version: 8.0.0
06-09 09:47:15.150 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] App version: 8.23.0.10
06-09 09:47:15.150 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] App activation state: Background
06-09 09:47:15.165 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.GenericUnsafe] Startup Phase 1 duration: 1202ms
06-09 09:47:15.178 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.GenericUnsafe] Startup Phase 2 duration: 1361ms
06-09 09:47:15.195 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Starting: HockeyAppService
06-09 09:47:15.210 I ReactHockeyApp: HockeyApp - initializing configuration
06-09 09:47:15.210 I ReactNativeJS: [#ffffffff-S] [TRACE] [JS.HockeyApp] Ignoring check for updates - PUBLIC build
06-09 09:47:15.224 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Finish: HockeyAppService: 28ms
06-09 09:47:15.224 I React: Check for new app crashes
06-09 09:47:15.248 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Starting: CrashStatusStore
06-09 09:47:15.252 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.GenericUnsafe] RN Entry
06-09 09:47:15.264 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] Last app launch time: undefined
06-09 09:47:15.271 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] _getAppLaunchState:subscribe:fired:0
06-09 09:47:15.321 I ReactNativeJS: [#ffffffff-S] [TRACE] [JS.HockeyApp] Last launch crashed: false
06-09 09:47:15.323 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Finish: CrashStatusStore: 74ms
06-09 09:47:15.326 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] SkypeId missing in Storage
06-09 09:47:15.668 E CredentialsFetcher: Can't parse xml
06-09 09:47:15.668 E CredentialsFetcher: /data/user/0/com.skype.raider/files/shared.xml (No such file or directory)
06-09 09:47:15.668 E CredentialsFetcher: 	java.io.FileInputStream.open0(FileInputStream.java:-2)
06-09 09:47:15.668 E CredentialsFetcher: 	java.io.FileInputStream.open(FileInputStream.java:200)
06-09 09:47:15.668 E CredentialsFetcher: 	java.io.FileInputStream.<init>(FileInputStream.java:150)
06-09 09:47:15.668 E CredentialsFetcher: 	com.skype.credentials.CredentialsFetcher.a(SourceFile:44)
06-09 09:47:15.668 E CredentialsFetcher: 	com.skype.credentials.SkypeCredentialsFetcherModule.fetchUserInfo(SourceFile:46)
06-09 09:47:15.668 E CredentialsFetcher: 	java.lang.reflect.Method.invoke(Method.java:-2)
06-09 09:47:15.668 E CredentialsFetcher: 	com.facebook.react.bridge.q.a(SourceFile:366)
06-09 09:47:15.668 E CredentialsFetcher: 	com.facebook.react.bridge.JavaModuleWrapper$b.invoke(SourceFile:283)
06-09 09:47:15.668 E CredentialsFetcher: 	com.facebook.react.bridge.JavaModuleWrapper.invoke(SourceFile:176)
06-09 09:47:15.668 E CredentialsFetcher: 	com.facebook.react.bridge.queue.NativeRunnable.run(SourceFile:-2)
06-09 09:47:15.668 E CredentialsFetcher: 	android.os.Handler.handleCallback(Handler.java:789)
06-09 09:47:15.668 E CredentialsFetcher: 	android.os.Handler.dispatchMessage(Handler.java:98)
06-09 09:47:15.668 E CredentialsFetcher: 	com.facebook.react.bridge.queue.a.dispatchMessage(SourceFile:31)
06-09 09:47:15.668 E CredentialsFetcher: 	android.os.Looper.loop(Looper.java:164)
06-09 09:47:15.668 E CredentialsFetcher: 	com.facebook.react.bridge.queue.MessageQueueThreadImpl$3.run(SourceFile:194)
06-09 09:47:15.668 E CredentialsFetcher: 	java.lang.Thread.run(Thread.java:764)
06-09 09:47:15.776 I DeviceUtilities: DeviceUtilities: currentOrientation
06-09 09:47:15.939 W React: StatusBarModule: Ignored status bar change, current activity is null.
06-09 09:47:15.944 W React: StatusBarModule: Ignored status bar change, current activity is null.
06-09 09:47:15.950 W React: StatusBarModule: Ignored status bar change, current activity is null.
06-09 09:47:15.951 I DeviceUtilities: DeviceUtilities: statusBarHeight
06-09 09:47:16.035 W ReactNativeJS: [#ffffffff-u] [WARN] [JS.ResponsiveWidthStore] DeviceUtilities.currentOrientation failed: [pii<E...>] causeId: f501113b
06-09 09:47:16.042 W ReactNativeJS: [#ffffffff-u] [WARN] [JS.GenericUnsafe] SafeAreaStore statusBarHeight failed: [pii<E...>]
06-09 09:47:23.296 I RNSlimcore: Clearing old logs
06-09 09:47:23.300 I SkyLibManager[TERMINATED:null]: clearOldLogs found 0 potential log files
06-09 09:47:29.987 I UpgradeContext: releaseWakeLock taskId 1
06-09 09:47:29.991 I SimpleWakefulService: Release WAKE_LOCK for taskId: 1 with startId: 2
06-09 09:47:29.996 I SimpleWakefulService: Removing Stop message
06-09 09:47:29.997 I SimpleWakefulService: Service destroyed
06-09 15:16:18.541 W ReactHockeyApp: RNHockeyApp: Failed to get existing metadata
06-09 15:16:18.541 W ReactHockeyApp: /data/user/0/com.skype.raider/files/HockeyAppCrashMetadata.json (No such file or directory)
06-09 15:16:18.541 W ReactHockeyApp: 	java.io.FileInputStream.open0(FileInputStream.java:-2)
06-09 15:16:18.541 W ReactHockeyApp: 	java.io.FileInputStream.open(FileInputStream.java:200)
06-09 15:16:18.541 W ReactHockeyApp: 	java.io.FileInputStream.<init>(FileInputStream.java:150)
06-09 15:16:18.541 W ReactHockeyApp: 	android.app.ContextImpl.openFileInput(ContextImpl.java:520)
06-09 15:16:18.541 W ReactHockeyApp: 	android.content.ContextWrapper.openFileInput(ContextWrapper.java:200)
06-09 15:16:18.541 W ReactHockeyApp: 	com.skype.hockeyapp.SkypeCrashListener.f(SourceFile:139)
06-09 15:16:18.541 W ReactHockeyApp: 	com.skype.hockeyapp.SkypeCrashListener.<init>(SourceFile:48)
06-09 15:16:18.541 W ReactHockeyApp: 	com.skype.hockeyapp.SkypeCrashListener.a(SourceFile:43)
06-09 15:16:18.541 W ReactHockeyApp: 	com.skype.hockeyapp.SkypeCrashManager.a(SourceFile:37)
06-09 15:16:18.541 W ReactHockeyApp: 	com.skype4life.SkypeApplication.onCreate(SourceFile:1042)
06-09 15:16:18.541 W ReactHockeyApp: 	android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1125)
06-09 15:16:18.541 W ReactHockeyApp: 	android.app.ActivityThread.handleBindApplication(ActivityThread.java:6056)
06-09 15:16:18.541 W ReactHockeyApp: 	android.app.ActivityThread.-wrap1(null:0)
06-09 15:16:18.541 W ReactHockeyApp: 	android.app.ActivityThread$H.handleMessage(ActivityThread.java:1764)
06-09 15:16:18.541 W ReactHockeyApp: 	android.os.Handler.dispatchMessage(Handler.java:105)
06-09 15:16:18.541 W ReactHockeyApp: 	android.os.Looper.loop(Looper.java:164)
06-09 15:16:18.541 W ReactHockeyApp: 	android.app.ActivityThread.main(ActivityThread.java:6938)
06-09 15:16:18.541 W ReactHockeyApp: 	java.lang.reflect.Method.invoke(Method.java:-2)
06-09 15:16:18.541 W ReactHockeyApp: 	com.android.internal.os.Zygote$MethodAndArgsCaller.run(Zygote.java:327)
06-09 15:16:18.541 W ReactHockeyApp: 	com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1374)
06-09 15:16:18.605 I DumpUploader: Preparing check for new crash dumps
06-09 15:16:18.611 I ReactApp: onCreate start
06-09 15:16:18.621 I DumpUploader: Started check for new crash dumps
06-09 15:16:18.623 I ReactApp: configureViewPools took 1ms
06-09 15:16:18.630 I DumpUploader: Marking dumps as known: 
06-09 15:16:18.678 I ReactApp: configureOkHttp took 55ms
06-09 15:16:18.679 I ReactApp: configureStetho took 0ms
06-09 15:16:18.692 I ReactApp: configureYoga took 13ms
06-09 15:16:18.696 I ReactApp: CsiManager.onCreate took 2ms
06-09 15:16:18.781 I ReactApp: mReactNativeHost.getReactInstanceManager took 85ms
06-09 15:16:18.782 I ReactApp: onCreate complete in 376ms
06-09 15:16:18.782 I React: Creating react context.
06-09 15:16:18.791 I ActivationExperiment: loadFromDisk:{"experimentList":[],"schemaVersion":"v1","totalWakeAttempts":1,"wakeUpList":[{"reason":"Upgrade","status":"NextWakeUpScheduled","time":1528438083838},{"reason":"RtcWakeUp","status":"WakeUpPending","time":1528765683839}]}, timeTaken(3 ms)
06-09 15:16:18.802 I SkypeCameraViewManager: init
06-09 15:16:18.817 I ActivationExperiment: cancelPendingRtcWake
06-09 15:16:18.848 I GradientImagePackage: createViewManagers
06-09 15:16:18.854 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.ink.AdditiveSurfaceViewManager
06-09 15:16:18.861 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.ink.AdditiveSurfaceViewShadowNode
06-09 15:16:18.879 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.uimanager.h
06-09 15:16:18.893 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.text.g
06-09 15:16:18.909 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.textinput.i
06-09 15:16:18.931 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.art.c
06-09 15:16:18.933 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.art.b
06-09 15:16:18.935 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.art.a
06-09 15:16:18.939 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.progressbar.b
06-09 15:16:18.951 W ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.text.frescosupport.a
06-09 15:16:18.953 W ViewManagerPropertyUpdater: Could not find generated setter for class com.brentvatne.react.ReactVideoViewManager
06-09 15:16:18.958 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skpcamera.SkypeCameraViewManager
06-09 15:16:18.966 W ViewManagerPropertyUpdater: Could not find generated setter for class com.customkeyboard.CustomKeyboardViewManager
06-09 15:16:18.970 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.slimcore.video.RNCallingVideoViewManager
06-09 15:16:18.975 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.slimcore.video.RNCallingVideoViewLocalManager
06-09 15:16:18.989 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.react.mediapicker.MediaPickerViewManager
06-09 15:16:18.995 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.react.mediapicker.c
06-09 15:16:19.000 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.skypemessagetextinput.view.RNViewManager
06-09 15:16:19.003 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.skypemessagetextinput.view.c
06-09 15:16:19.004 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.reactnativesprites.SpriteViewManager
06-09 15:16:19.008 W ViewManagerPropertyUpdater: Could not find generated setter for class com.projectseptember.RNGL.GLCanvasManager
06-09 15:16:19.011 W ViewManagerPropertyUpdater: Could not find generated setter for class com.github.alinz.reactnativewebviewbridge.WebViewBridgeManager
06-09 15:16:19.018 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapCalloutManager
06-09 15:16:19.032 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapMarkerManager
06-09 15:16:19.049 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapPolylineManager
06-09 15:16:19.073 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapPolygonManager
06-09 15:16:19.077 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapCircleManager
06-09 15:16:19.082 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapManager
06-09 15:16:19.090 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapLiteManager
06-09 15:16:19.091 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.maps.AirMapUrlTileManager
06-09 15:16:19.093 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.react.videofxp.VideoFXPViewManager
06-09 15:16:19.106 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.virtualmessageview.VirtualMessageViewControllerManager
06-09 15:16:19.113 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.react.clippedview.ClippedViewManager
06-09 15:16:19.115 W ViewManagerPropertyUpdater: Could not find generated setter for class com.BV.LinearGradient.LinearGradientManager
06-09 15:16:19.118 W ViewManagerPropertyUpdater: Could not find generated setter for class com.airbnb.android.react.lottie.LottieAnimationViewManager
06-09 15:16:19.122 W ViewManagerPropertyUpdater: Could not find generated setter for class com.microsoft.react.gradientimage.GradientImageViewManager
06-09 15:16:19.124 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.qrcode.QRCodeViewManager
06-09 15:16:19.127 W ViewManagerPropertyUpdater: Could not find generated setter for class com.skype.camera.imagefilter.ImageFilterManager
06-09 15:16:19.530 W JavaModuleHelper: Could not find generated custom module provider
06-09 15:16:19.532 W React: There is no generated module helper for module: SKPSkypeMessageTextInputModule using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.533 W React: There is no generated module helper for module: RNReload using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.533 W React: There is no generated module helper for module: RNBackgroundTimer using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.534 W React: There is no generated module helper for module: ImagePickerManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.534 W React: There is no generated module helper for module: FrescoModule using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.534 W React: There is no generated module helper for module: SourceCode using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.534 W React: There is no generated module helper for module: SoundPlayer using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.534 W React: There is no generated module helper for module: AdvertisementUtilities using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.535 W React: There is no generated module helper for module: RNCookieManagerAndroid using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.535 W React: There is no generated module helper for module: NativeEntropy using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.535 W React: There is no generated module helper for module: RNAppUpgrade using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.535 W React: There is no generated module helper for module: DeviceInfo using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.535 W React: There is no generated module helper for module: RNGeocoder using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.536 W React: There is no generated module helper for module: ExtendedAppState using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.536 W React: There is no generated module helper for module: Adjust using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.536 W React: There is no generated module helper for module: PermissionsManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.536 W React: There is no generated module helper for module: RNStorage using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.536 W React: There is no generated module helper for module: AndroidBadges using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.537 W React: There is no generated module helper for module: RNBackgroundExecution using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.537 W React: There is no generated module helper for module: VideoFXP using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.537 W React: There is no generated module helper for module: RNDocumentPicker using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.537 W React: There is no generated module helper for module: TimeZoneManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.537 W React: There is no generated module helper for module: PlatformConstants using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.538 W React: There is no generated module helper for module: DeviceUtilities using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.538 W React: There is no generated module helper for module: SoundRecorder using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.538 W React: There is no generated module helper for module: CortanaSignals using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.538 W React: There is no generated module helper for module: FileEncryptionNative using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.538 W React: There is no generated module helper for module: DeviceSettings using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.539 W React: There is no generated module helper for module: ContextMenuAndroid using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.539 W React: There is no generated module helper for module: Contacts using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.539 W React: There is no generated module helper for module: RNCommandInvoker using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.539 W React: There is no generated module helper for module: RNHockeyApp using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.540 W React: There is no generated module helper for module: ExternalBrowser using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.540 W React: There is no generated module helper for module: StyleTransfer using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.541 W React: There is no generated module helper for module: UrlUtil using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.541 W React: There is no generated module helper for module: SnapshotManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.541 W React: There is no generated module helper for module: MediaPicker using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.541 W React: There is no generated module helper for module: CustomKeyboard using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.541 W React: There is no generated module helper for module: AirMapModule using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.542 W React: There is no generated module helper for module: AssetReader using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.542 W React: There is no generated module helper for module: RNPushAndroid using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.542 W React: There is no generated module helper for module: ShareSheet using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.542 W React: There is no generated module helper for module: CallIntent using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.542 W React: There is no generated module helper for module: RNGLContext using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.543 W React: There is no generated module helper for module: ZipUtil using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.543 W React: There is no generated module helper for module: RNViewConfig using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.543 W React: There is no generated module helper for module: FingerprintingLib using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.543 W React: There is no generated module helper for module: ShareToApp using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.543 W React: There is no generated module helper for module: RNNetworkInfo using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.543 W React: There is no generated module helper for module: ClientLogging using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.543 W React: There is no generated module helper for module: AudioManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.544 W React: There is no generated module helper for module: TokenShareModule using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.544 W React: There is no generated module helper for module: CampaignReceiver using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.544 W React: There is no generated module helper for module: EnvironmentInfo using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.544 W React: There is no generated module helper for module: RNSlimcore using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.545 W React: There is no generated module helper for module: RNSkypeCredentialsFetcher using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.545 W React: There is no generated module helper for module: ImageResizerAndroid using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.546 W React: There is no generated module helper for module: RNManualFileCache using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.546 W React: There is no generated module helper for module: FileTracker using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.546 W React: There is no generated module helper for module: IncomingCallInteractionManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.546 W React: There is no generated module helper for module: RNKeychainManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.547 W React: There is no generated module helper for module: RNGraphicsContext using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.547 W React: There is no generated module helper for module: RNUrlRequest using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.547 W React: There is no generated module helper for module: SkypeCamera using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.547 W React: There is no generated module helper for module: SplashScreenNotifier using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.547 W React: There is no generated module helper for module: CallMonitor using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.547 W React: There is no generated module helper for module: AndroidSmsManager using FallbackModuleHelper which works way slower. Consider enabling apt generation for this module in order to improve startup performance
06-09 15:16:19.592 I SmsHandlingContext: init()
06-09 15:16:19.594 W ReactApp: registerMemoryTrimmable current size: 0
06-09 15:16:19.594 W ReactApp: registerMemoryTrimmable current size: 1
06-09 15:16:19.674 I AudioManagerModule: initialize (causeId 2399b565)
06-09 15:16:19.675 I AudioManagerModule: AudioManagerModule.initialize took 2ms
06-09 15:16:19.675 I AudioOptions: initialize (causeId 2399b565)
06-09 15:16:19.679 I SkypeCameraModule: SkypeCameraModule initialize
06-09 15:16:19.680 I WiredHeadsetReceiver: Registered receiver
06-09 15:16:19.683 I WiredHeadsetReceiver: addListener (causeId: 2399b565)
06-09 15:16:19.684 I AudioOptions: WiredHeadsetReceiver.headsetStateChanged UNPLUGGED (causeId 2399b565)
06-09 15:16:19.726 I TokenShareModule: getAccounts() called, returned with list size 0
06-09 15:16:19.789 I BluetoothReceiver: Received sticky intent android.media.ACTION_SCO_AUDIO_STATE_UPDATED
06-09 15:16:19.789 I BluetoothReceiver: Registered receiver
06-09 15:16:19.790 I BluetoothReceiver: loadAlreadyConnectedDevices (causeId: 2399b565)
06-09 15:16:19.791 I BluetoothReceiver: onReceive action android.media.ACTION_SCO_AUDIO_STATE_UPDATED (causeId f053f5d5)
06-09 15:16:19.791 I BluetoothReceiver: handleScoAudioStateChange prevState: -1 state: 0 (causeId: f053f5d5)
06-09 15:16:19.791 I BluetoothReceiver: scoDisconnected
06-09 15:16:19.797 I BluetoothReceiver: addListener (causeId: 2399b565)
06-09 15:16:19.797 I BluetoothReceiver: onReceive action android.media.ACTION_SCO_AUDIO_STATE_UPDATED (causeId b564d857)
06-09 15:16:19.798 I BluetoothReceiver: handleScoAudioStateChange prevState: -1 state: 0 (causeId: b564d857)
06-09 15:16:19.798 I BluetoothReceiver: scoDisconnected
06-09 15:16:19.798 I AudioOptions: BluetoothReceiver.scoDisconnected (causeId b564d857)
06-09 15:16:19.798 I BluetoothReceiver: onReceive action android.media.SCO_AUDIO_STATE_CHANGED (causeId e8f61d18)
06-09 15:16:19.799 I BluetoothReceiver: handleScoAudioStateChange prevState: 0 state: 0 (causeId: e8f61d18)
06-09 15:16:19.799 I BluetoothReceiver: scoDisconnected
06-09 15:16:19.799 I AudioOptions: BluetoothReceiver.scoDisconnected (causeId e8f61d18)
06-09 15:16:19.802 I BluetoothReceiver: createServiceListener (causeId: 2399b565)
06-09 15:16:19.821 I ModernAudioDeviceMonitor: addListener (causeId: 2399b565)
06-09 15:16:19.821 I AudioOptions: ModernAudioDeviceMonitor.availableAudioDeviceTypesChanged headphones: false usb: false (causeId 2399b565)
06-09 15:16:19.827 I ModernAudioDeviceMonitor: initialization headphones: false, usb: false, devices: [[1:TYPE_BUILTIN_EARPIECE], [2:TYPE_BUILTIN_SPEAKER], [6:TYPE_BUILTIN_MIC], [8:TYPE_TELEPHONY]] (causeId: c2a8ab41)
06-09 15:16:19.828 I ModernAudioDeviceMonitor: onAudioDevicesAdded headphones: false, usb: false, devices: [[1:TYPE_BUILTIN_EARPIECE], [2:TYPE_BUILTIN_SPEAKER], [6:TYPE_BUILTIN_MIC], [8:TYPE_TELEPHONY]] (causeId: 1a96c213)
06-09 15:16:19.829 I ModernAudioDeviceMonitor: onAudioDevicesAdded headphones: false, usb: false, devices: [[1:TYPE_BUILTIN_EARPIECE], [2:TYPE_BUILTIN_SPEAKER], [6:TYPE_BUILTIN_MIC], [8:TYPE_TELEPHONY]] (causeId: d4eee03f)
06-09 15:16:19.834 I TelephoneStateListener: Registering phone state listener (causeId 2399b565)
06-09 15:16:19.849 I AudioManagerModule: TelephoneStateListener.init took 24ms
06-09 15:16:19.854 I AudioManagerModule: Sending output changed event to EARPIECE (causeId 2399b565)
06-09 15:16:19.873 I TelephoneStateListener: Forcing update of phone state (causeId 2399b565)
06-09 15:16:19.881 I AudioManagerModule: mergedSettingForSettings default output route computed as SPEAKER (causeId: 2399b565)
06-09 15:16:19.881 I AudioManagerModule: calcSettingsAndUpdate: current: (stream=USE_DEFAULT_STREAM_TYPE, mode=MODE_INVALID, focus=DOES NOT WANT, route=EARPIECE), merged: (stream=USE_DEFAULT_STREAM_TYPE, mode=MODE_NORMAL, focus=DOES NOT WANT, route=SPEAKER), modes: [], background: false, focusState: Unknown, inPhoneCall: false (causeId 2399b565)
06-09 15:16:19.881 I AudioManagerModule: Setting audio mode MODE_INVALID -> MODE_NORMAL (causeId 2399b565)
06-09 15:16:19.889 I AudioManagerModule: Setting audio route EARPIECE -> SPEAKER (causeId 2399b565)
06-09 15:16:19.889 I AudioOptions: routeAudioOutput SPEAKER (causeId 2399b565)
06-09 15:16:19.890 I AudioOptions: intRouteAudioOutput SPEAKER userAction=true (causeId 2399b565)
06-09 15:16:19.891 I TelephoneStateListener: onCallStateChanged 0 (causeId beca449c)
06-09 15:16:19.892 I TelephoneStateListener: Forcing update of phone state (causeId b564d857)
06-09 15:16:19.892 I AudioManagerModule: Sending output changed event to SPEAKER (causeId 2399b565)
06-09 15:16:19.895 I AudioOptions: Active audio output destination is SPEAKER (causeId 2399b565)
06-09 15:16:19.902 I AudioManagerModule: mergedSettingForSettings default output route computed as SPEAKER (causeId: b564d857)
06-09 15:16:19.904 I AudioManagerModule: calcSettingsAndUpdate: current: (stream=USE_DEFAULT_STREAM_TYPE, mode=MODE_NORMAL, focus=DOES NOT WANT, route=SPEAKER), merged: (stream=USE_DEFAULT_STREAM_TYPE, mode=MODE_NORMAL, focus=DOES NOT WANT, route=SPEAKER), modes: [], background: false, focusState: Unknown, inPhoneCall: false (causeId b564d857)
06-09 15:16:19.905 I TelephoneStateListener: Forcing update of phone state (causeId e8f61d18)
06-09 15:16:19.920 I AudioManagerModule: mergedSettingForSettings default output route computed as SPEAKER (causeId: e8f61d18)
06-09 15:16:19.921 I AudioManagerModule: calcSettingsAndUpdate: current: (stream=USE_DEFAULT_STREAM_TYPE, mode=MODE_NORMAL, focus=DOES NOT WANT, route=SPEAKER), merged: (stream=USE_DEFAULT_STREAM_TYPE, mode=MODE_NORMAL, focus=DOES NOT WANT, route=SPEAKER), modes: [], background: false, focusState: Unknown, inPhoneCall: false (causeId e8f61d18)
06-09 15:16:19.922 I TelephoneStateListener: Forcing update of phone state (causeId 2399b565)
06-09 15:16:19.925 I AudioManagerModule: mergedSettingForSettings default output route computed as SPEAKER (causeId: 2399b565)
06-09 15:16:19.925 I AudioManagerModule: calcSettingsAndUpdate: current: (stream=USE_DEFAULT_STREAM_TYPE, mode=MODE_NORMAL, focus=DOES NOT WANT, route=SPEAKER), merged: (stream=USE_DEFAULT_STREAM_TYPE, mode=MODE_NORMAL, focus=DOES NOT WANT, route=SPEAKER), modes: [], background: false, focusState: Unknown, inPhoneCall: false (causeId 2399b565)
06-09 15:16:20.645 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'StaticTask.OnAppUpdated'
06-09 15:16:20.648 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'StaticTask.OnAppUpdatedRetry'
06-09 15:16:20.711 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'SignInOnUserSessionConnected'
06-09 15:16:20.712 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'SignInOnUserSessionConnectedRetry'
06-09 15:16:20.712 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'SignInOnDefaultMSAConnected'
06-09 15:16:20.713 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'SignInOnDefaultMSAConnectedRetry'
06-09 15:16:20.715 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'OnMaintenanceWindowStart'
06-09 15:16:20.715 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.HeadlessJsTask] registerHeadlessTaskCallbacks called for 'OnMaintenanceWindowStartRetry'
06-09 15:16:20.744 I RNAppUpgrade: Getting app launch attribution state = false
06-09 15:16:20.745 I RNAppUpgrade: hasOldSessionPreferences:false
06-09 15:16:20.752 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] Preparing to handle App Upgrade Event
06-09 15:16:20.753 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] Preparing to handle Rtc Wake Event
06-09 15:16:20.754 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] _setUpAppLaunchStateChangeListener
06-09 15:16:20.756 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] _setUpNoticationClickListener
06-09 15:16:20.758 I RNAppUpgrade: initialize
06-09 15:16:20.759 I UpgradeContext: acquireWakeLock taskId 1
06-09 15:16:20.762 I SimpleWakefulService: Service created
06-09 15:16:20.763 I SimpleWakefulService: Acquire WAKE_LOCK for taskId: 1 with startId: 1
06-09 15:16:20.763 I RNAppUpgrade: processPendingIntents
06-09 15:16:20.764 I RNAppUpgrade: processPendingIntents:delayedIntentQueue size(0)
06-09 15:16:20.764 I RNAppUpgrade: initialize
06-09 15:16:20.871 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Locale initialized to [en_CA]
06-09 15:16:20.872 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Country code is [CA]
06-09 15:16:20.887 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Device Id: fkgXjGl17eI
06-09 15:16:20.888 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Device Manufacturer: samsung
06-09 15:16:20.889 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Device Model: SM-G955W
06-09 15:16:20.890 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Device OS version: 8.0.0
06-09 15:16:20.891 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] App version: 8.23.0.10
06-09 15:16:20.892 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] App activation state: Background
06-09 15:16:20.912 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.GenericUnsafe] Startup Phase 1 duration: 1223ms
06-09 15:16:20.923 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.GenericUnsafe] Startup Phase 2 duration: 1096ms
06-09 15:16:20.934 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Starting: HockeyAppService
06-09 15:16:20.949 I ReactHockeyApp: HockeyApp - initializing configuration
06-09 15:16:20.950 I ReactNativeJS: [#ffffffff-S] [TRACE] [JS.HockeyApp] Ignoring check for updates - PUBLIC build
06-09 15:16:20.953 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Finish: HockeyAppService: 18ms
06-09 15:16:20.958 I React: Check for new app crashes
06-09 15:16:20.974 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Starting: CrashStatusStore
06-09 15:16:20.977 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.GenericUnsafe] RN Entry
06-09 15:16:20.989 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] Last app launch time: undefined
06-09 15:16:20.996 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.AppUpgrade] _getAppLaunchState:subscribe:fired:0
06-09 15:16:21.043 I ReactNativeJS: [#ffffffff-S] [TRACE] [JS.HockeyApp] Last launch crashed: false
06-09 15:16:21.044 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] Finish: CrashStatusStore: 70ms
06-09 15:16:21.048 I ReactNativeJS: [#ffffffff-u] [TRACE] [JS.Startup] SkypeId missing in Storage
06-09 15:16:21.374 E CredentialsFetcher: Can't parse xml
06-09 15:16:21.374 E CredentialsFetcher: /data/user/0/com.skype.raider/files/shared.xml (No such file or directory)
06-09 15:16:21.374 E CredentialsFetcher: 	java.io.FileInputStream.open0(FileInputStream.java:-2)
06-09 15:16:21.374 E CredentialsFetcher: 	java.io.FileInputStream.open(FileInputStream.java:200)
06-09 15:16:21.374 E CredentialsFetcher: 	java.io.FileInputStream.<init>(FileInputStream.java:150)
06-09 15:16:21.374 E CredentialsFetcher: 	com.skype.credentials.CredentialsFetcher.a(SourceFile:44)
06-09 15:16:21.374 E CredentialsFetcher: 	com.skype.credentials.SkypeCredentialsFetcherModule.fetchUserInfo(SourceFile:46)
06-09 15:16:21.374 E CredentialsFetcher: 	java.lang.reflect.Method.invoke(Method.java:-2)
06-09 15:16:21.374 E CredentialsFetcher: 	com.facebook.react.bridge.q.a(SourceFile:366)
06-09 15:16:21.374 E CredentialsFetcher: 	com.facebook.react.bridge.JavaModuleWrapper$b.invoke(SourceFile:283)
06-09 15:16:21.374 E CredentialsFetcher: 	com.facebook.react.bridge.JavaModuleWrapper.invoke(SourceFile:176)
06-09 15:16:21.374 E CredentialsFetcher: 	com.facebook.react.bridge.queue.NativeRunnable.run(SourceFile:-2)
06-09 15:16:21.374 E CredentialsFetcher: 	android.os.Handler.handleCallback(Handler.java:789)
06-09 15:16:21.374 E CredentialsFetcher: 	android.os.Handler.dispatchMessage(Handler.java:98)
06-09 15:16:21.374 E CredentialsFetcher: 	com.facebook.react.bridge.queue.a.dispatchMessage(SourceFile:31)
06-09 15:16:21.374 E CredentialsFetcher: 	android.os.Looper.loop(Looper.java:164)
06-09 15:16:21.374 E CredentialsFetcher: 	com.facebook.react.bridge.queue.MessageQueueThreadImpl$3.run(SourceFile:194)
06-09 15:16:21.374 E CredentialsFetcher: 	java.lang.Thread.run(Thread.java:764)
06-09 15:16:21.452 I DeviceUtilities: DeviceUtilities: currentOrientation
06-09 15:16:21.571 W React: StatusBarModule: Ignored status bar change, current activity is null.
06-09 15:16:21.577 W React: StatusBarModule: Ignored status bar change, current activity is null.
06-09 15:16:21.583 W React: StatusBarModule: Ignored status bar change, current activity is null.
06-09 15:16:21.583 I DeviceUtilities: DeviceUtilities: statusBarHeight
06-09 15:16:21.639 W ReactNativeJS: [#ffffffff-u] [WARN] [JS.ResponsiveWidthStore] DeviceUtilities.currentOrientation failed: [pii<E...>] causeId: 4952e3f2
06-09 15:16:21.642 W ReactNativeJS: [#ffffffff-u] [WARN] [JS.GenericUnsafe] SafeAreaStore statusBarHeight failed: [pii<E...>]
06-09 15:16:29.381 I RNSlimcore: Clearing old logs
06-09 15:16:29.388 I SkyLibManager[TERMINATED:null]: clearOldLogs found 0 potential log files
06-09 15:16:35.801 I UpgradeContext: releaseWakeLock taskId 1
06-09 15:16:35.805 I SimpleWakefulService: Release WAKE_LOCK for taskId: 1 with startId: 2
06-09 15:16:35.808 I SimpleWakefulService: Removing Stop message
06-09 15:16:35.809 I SimpleWakefulService: Service destroyed
