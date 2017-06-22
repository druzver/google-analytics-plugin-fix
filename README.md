форк плагина google-analytics-plugin  для Cordova

при использовании оригинального плагина, Apple Store выдавало сообщение

Your app is using the Advertising Identifier (IDFA).
You must either provide details about the IDFA usage or remove it from the app and submit your binary again.



- удалены зависимости из plugin.xml


<source-file src="ios/libAdIdAccess.a" framework="true" />
<framework src="AdSupport.framework" />
