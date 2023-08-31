# Uncomment the next line to define a global platform for your project
# platform :ios, '9.3'

workspace 'SampleModularArchitecture.xcworkspace'
project 'SampleModularArchitecture.xcodeproj'

def networking_pod
pod 'Networking', :path => 'DevPods/Networking'
end

def development_pods
    networking_pod
end

target 'SampleModularArchitecture' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for SampleModularArchitecture
   development_pods
end

target 'Networking_Example' do
   use_frameworks!
   project 'DevPods/Networking/Example/Networking.xcodeproj'
   networking_pod
end



