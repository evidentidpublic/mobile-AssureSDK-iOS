# ![Evident logo](res/evident-logo_56x44.png)AssureSDK for iOS
Integrate Evident AssureSDK for iOS into your app.

Download framework and demo app from [releases](https://github.com/evidentidpublic/mobile-AssureSDK-iOS/releases)

For integration with Cocoapods add to your Podfile:

```
#
# Add Evident ID podspec repo to pod sources
# CAVEAT: 
# When adding any sources, you also need to add the 
# standard Cocoapods repo.
#
source 'https://github.com/cocoapods/specs.git'
source 'git@github.com:evidentidpublic/mobile-podspecs.git'
[...]
target 'your-target' do
	pod 'AssureSDK', '1.1.3'
end

``` 


