source 'https://github.com/CocoaPods/Specs.git'
platform :osx, '10.10'
use_frameworks!

workspace 'Maria.xcworkspace'

project 'Maria.xcodeproj'
project 'YouGet.xcodeproj'

def starscream
    pod 'Starscream', :git => 'https://github.com/daltoniam/Starscream.git'
end

def swifty_json
    pod 'SwiftyJSON', :git => 'https://github.com/SwiftyJSON/SwiftyJSON.git'
end

def swifty_userdefaults
    pod 'SwiftyUserDefaults', :git => 'https://github.com/radex/SwiftyUserDefaults.git'
end

def aria2rpc
    pod 'Aria2RPC', :git => 'https://github.com/ShinCurry/Aria2RPC.git'
end

def aria2core
    pod 'Aria2Core', :git => 'https://github.com/ShinCurry/Aria2Core.git'
end

def sparkle
    pod 'Sparkle'
end


target 'Maria' do
    project 'Maria'
    
    starscream
    swifty_json
    swifty_userdefaults
    aria2rpc
    aria2core
    sparkle

end

target 'Maria Widget' do
    project 'Maria'
    
    starscream
    swifty_json
    swifty_userdefaults
    aria2rpc
end

target 'YouGet' do
    project 'YouGet'
    
    swifty_json
end
