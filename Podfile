# Uncomment the next line to define a global platform for your project
source 'https://github.com/CocoaPods/Specs.git'
workspace 'loafwallet.xcworkspace'
project 'loafwallet.xcodeproj', 'Debug' => :debug,'Release' => :release
use_frameworks!


#Shared Cocoapods
def shared_pods
  pod 'Firebase/Crashlytics' 
  pod 'Firebase/Analytics'

  # add after v2.6.0 pod 'SwiftLint'
end

def shared_watchOS_pods
end

target 'loafwallet' do
  platform :ios, '12.0'
  shared_pods
  
  target 'loafwalletTests' do
    inherit! :search_paths
  end 
  
end
 
