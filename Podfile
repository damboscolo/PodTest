# Uncomment this line to define a global platform for your project
 platform :ios, '9.0'
 use_frameworks!

# Pods for MobPago
def ui_pods
    pod 'TKInsertCodeView', :git => 'https://github.com/tokenlab/TKInsertCodeView.git'
end

target 'PodTest' do
    use_frameworks!
    ui_pods

    target 'PodTestTests' do
        #inherit! :search_paths
        # Pods for testing
    end
end


post_install do |installer|
    installer.pods_project.targets.each do |target|
        puts target.name
    end
end
