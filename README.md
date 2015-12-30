# documents
###放置公用文件
>
location.properties配置
>
ossrhUsername=xxx
>
ossrhPassword=xxx
>
bintray.apikey=xxxxxxx
>
bintray.user=nicccccccccce
>
###项目根中配置gradle.properties
>
signing.keyId=2DCBEA60
>
signing.password=xxxxx
>
signing.secretKeyRingFile=J:/AndroidStudioProjects/ZcodeScanner.gpg
>
DEVELOPER_NAME=nicccccccccce
>
siteUrl=https\://github.com/nicccccccccce/android-rippleView
>
gitUrl=https\://github.com/nicccccccccce/android-rippleView.git
>
POM_PACKAING=aar
>
POM_ARTIFACT_ID=app
>
scmGitUrl=scm\:git@github.com\:github.com/nicccccccccce/android-rippleView.git
>
DEVELOPER_EMAIL=huxian901001@126.com
>
DEVELOPER_ID=nicccccccccce
>
gitUrl2=git@github.com\:github.com/nicccccccccce/android-rippleView.git
>
POM_DESCRIPTION=Android Commonly used utils
>
PUSH_NAME=android-rippleView
>
###项目根中build.gradle配置
>buildscript {
> repositories {
>//        jcenter()
 >       jcenter {
  >          url "http://jcenter.bintray.com/"
 >       }
>
>    }
>    dependencies {
>        classpath 'com.android.tools.build:gradle:1.2.3'
>        classpath 'com.github.dcendents:android-maven-gradle-plugin:1.3'
 >       classpath 'com.jfrog.bintray.gradle:gradle-bintray-plugin:1.2'

>        // NOTE: Do not place your application dependencies here; they belong
 >       // in the individual module build.gradle files


>    }
>}

>allprojects {
 >   repositories {
>//        jcenter()
>        maven  {
>            url "http://repo1.maven.org/maven2"
>        }
>    }
>}
###modules中build.gradle
>apply plugin: 'com.android.library'
>version ="1.0.2"
>group ="com.github.nicccccccccce.rippleview"
>//apply from: 'gradle-bintray-push.gradle'

