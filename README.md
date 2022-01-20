# DummyPod
# Pod creation steps

1. pod spec create DummmyLibrary
2. Add/Update podspec file - 
  1. Add description
  2. Change homepage
  3. Add license
  4. Spec source
  5. Source files

3. pod spec lint DummyLibrary.podspec --allow-warnings
4. Add pod file in example project     
pod 'DummyLibrary', :path => "Path of the pod project"
