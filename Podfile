# Uncomment the next line to define a global platform for your project
platform :ios, '9.0'
workspace 'CocoaPods-Issue7461.xcworkspace'

target 'CocoaPods-Issue7461'

pod 'yoga', :path => 'node_modules/react-native/ReactCommon/yoga'
pod 'React', path: 'node_modules/react-native', :subspecs => [
'Core',
'BatchedBridge',
'DevSupport',
'RCTActionSheet',
'RCTAnimation',
'RCTCameraRoll',
'RCTGeolocation',
'RCTImage',
'RCTNetwork',
'RCTPushNotification',
'RCTSettings',
'RCTText',
'RCTVibration',
'RCTWebSocket',
'RCTLinkingIOS',
]

target 'RNRandomBytes' do
    project 'node_modules/react-native-randombytes/RNRandomBytes.xcodeproj', 'Qa' => :release
end

target 'LRDRCTSimpleToast' do
    project 'node_modules/react-native-simple-toast/ios/LRDRCTSimpleToast.xcodeproj', 'Qa' => :release
end

target 'RNSensitiveInfo' do
    project 'node_modules/react-native-sensitive-info/ios/RNSensitiveInfo.xcodeproj', 'Qa' => :release
end
