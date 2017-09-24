# FCM_Aplicativo_Ionic



Porjeto ionic 

https://github.com/mexists/ionic-fcm-starter

https://github.com/mexists/ionic-fcm-starter/blob/master/TUTORIAL.md


1 - Instalacao : 
 
	npm install 

2 - Instalacao Plataforma Android :  

	ionic platform add android	


3 - Adicionar plugin FCM 

	ionic plugin add cordova-plugin-fcm


4 - Instalacao do bower 

	npm install -g bower


5 - Instalacao cordova  

	bower install ngCordova


6 - Alterar arquivo config.xml com o pacote do FCM 

	<widget id="com.br.teste" />

7 - Fazer donwload do arquivo google-services.json e colocar nos diretorios: 

	C:\Users\lprates\Desktop\fcm\ionic-fcm-starter-master e 

	C:\Users\lprates\Desktop\fcm\ionic-fcm-starter-master\platforms\android


8 - Alterar propriedade key do json no arquivo : 

	C:\Users\lprates\Desktop\fcm\ionic-fcm-starter-master\www\js\controller.js  


9 - Construir Android 

	ionic cordova build android 


10 - Executar no celular 

	ionic cordova run android   



