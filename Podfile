source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '9.0'
use_frameworks!

def import_test_pods
  import_pods
  pod 'Quick', '0.9.2'
  pod 'Nimble', '4.0.1'
end

def import_pods
  pod 'PusherSwift'
end

target 'Pusher-Example' do
  project 'Pusher-Example'
  platform :ios, '9.0'
  import_pods
end

target 'Pusher-ExampleTests' do
  project 'Pusher-Example'
  platform :ios, '9.0'
  import_test_pods
end
