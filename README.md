# DummyPod
# Pod creation steps
1. pod spec create DummmyLibrary

Add/Update podspec file - 
1. Add description
2. Change homepage
3. Add license
4. Spec source
5. Source files

2. pod spec lint DummyLibrary.podspec --allow-warnings
3. Add pod file in example project     
pod 'DummyLibrary', :path => "Path of the pod project"
