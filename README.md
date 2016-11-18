# phonegap-template-webvr


A PhoneGap template for the [WebVR Boilerplate](https://github.com/borismus/webvr-boilerplate), designed for use on phones supporting iOS 8 or greater and Android (7.0 Nougat or greater preferable, older Android OSes will need to use the Crosswalk plugin).

To install:

    phonegap create hello com.example.hello HelloWorld --template phonegap-template-webvr
   
Don’t forget to add the Crosswalk plugin beforehand if you are on an older Android (< 7.0) version:

    phonegap plugin add cordova-plugin-crosswalk-webview

More info about PhoneGap app templates [here](https://cordova.apache.org/docs/en/latest/guide/cli/template.html).


## Credits

The WebVR Boilerplate contents is from https://github.com/borismus/webvr-boilerplate

To update with the latest from that repo execute in the top-level directory:

        git remote add webvr-boilerplate https://github.com/borismus/webvr-boilerplate.git
        git subtree pull --prefix=template_src/www --squash webvr-boilerplate master
