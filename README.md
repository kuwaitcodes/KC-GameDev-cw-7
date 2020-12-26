# gamedev-cw-7
لعبة الصاروخ - تصميم المركبة


Gamedev-cw-7
قم بتصميم أي مركبة تشاء تصميمها
أضف الألوان إلى هذه المركبة
ضع كل الgameObjects تحت gameObject فاضي 
قم بعمل reset للtransform لمركبتك
صمم أرضية المرحلة من خلال استخدام cube
صمم نقطة انطلاق و نقطة وصول

Gamedev-cw-8
أضف RigidBody على المركبة (3D RigidBody)
أنشئ دالة Thrust() - عندما يغط المستخدم Space تتحرم المركبة إلى الأعلى
أنشئ دالة Rotate()  - عندما يضغط المستخدم A أو D تتدحرج المركبة إلى اليمين أو اليسار


Gamedev-cw-9
أضف Audio Source component ألى مركبتك
في دالة Start، قم تعيين الAudio Source و أعطه اسم vehicleAudioSource
في الscript أضف AudioClip و أعطه اسم mainEngine
قم تضبيط دالة Thrust() لتستخرج هذه الأصوات
جمد ال Z position
جمد ال X and Y rotation
في دالة الRotate() جمد الrotations يدويا

يمكنك تحميل الأصوات من خلال هذا الرابط You can get your audio from: https://freesound.org/

Gamedev-cw-10
أضف ملصق “Friendly” لأي شيئ لا يضر اللاعب 
أضف ملصق “Finish” لنقطة الوصول
قم باستخدام دالة OnCollisionEnter  - أذا قام اللاعب بالاصتدام بأاي جسد غير نقطة الوصول: print(“No worries!”)
اذا أصطدم اللاعب بنقطة الوصول اكتب print(“You win!”); 

Gamedev-cw-11
صمم المراحل ٢ و ٣
عند الوصول لنهاية أي مرحلة، يذهب اللاعب إلى المرحلة القادمة
المرحلة تظهر بعد ٣ ثواني من الوصول إلى نقطة الانتهاء

Gamedev-cw-12
أضف تأثير بصري و صوتي للفوز - يظهر و يسمع عندما يصل الاعب إلى منطقة الانتهاء
أضف تأثير بصري و صوتي للخسارة - يظهر و يسمع عندما يصتدم اللاعب
أضف صوت للمحرك Thrust
أضف مؤثرات صوتية كخلفية للعبة
