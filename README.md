# phonegap-template-webvr


A PhoneGap template for the [WebVR Boilerplate](https://github.com/borismus/webvr-boilerplate).

To install:

   cordova create hello com.example.hello HelloWorld --template phonegap-template-webvr
   
More info about PhoneGap app templates [here](https://cordova.apache.org/docs/en/latest/guide/cli/template.html).


## Credits

The WebVR Boilerplate contents is from https://github.com/borismus/webvr-boilerplate

To update with the latest from that repo execute in the top-level directory:

        git remote add webvr-boilerplate https://github.com/borismus/webvr-boilerplate.git
        git subtree pull --prefix=template_src/www --squash webvr-boilerplate master
