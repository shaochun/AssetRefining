# --------------------------------
# - 所有的特效檔案存於此處。
# --------------------------------

Effect/                 

	# 此處Common的含義是：既可以被InGame調用，又可以被Lobby調用的資源；
	Common/             
		
		Animation/
			AM_<英文名稱>.anim
			AC_<英文名稱>.controller
			
		# 模型復用，所有的特效模型 存於此處。
		FBX/             
			SK_<英文名稱>.FBX
			   
		Material/
			MT_<英文名稱>.mat
			
		   
		Prefab/
			PF_<英文名稱>.prefab 
		   
		# 貼圖復用，所有的特效貼圖 存於此處。
		Texture/                
			TX_<英文名稱>_D.png   
			TX_<英文名稱>_N.png
		   
	# InGame環境下使用的資源
	InGame/                     
	
		<數字>_<英文名稱>      #例：019020_Hawk
		 
			 Animation/
				AM_<英文名稱>.anim
				AC_<英文名稱>.controller

			 Material/
				MT_<英文名稱>.mat

			 Prefab/
				PF_<英文名稱>.prefab  
		  
		<數字>_<英文名稱>      #例：019040_Molos
			 
			 (子資料夾內容同上)
			 
		  
		# 戰鬥相關特效；例如：暴擊提示等
		Battle                 
		 
			 Animation/
				 AM_<英文名稱>.anim
				 AC_<英文名稱>.controller

			 Material/
				 MT_<英文名稱>.mat

			 Prefab/
				 PF_<英文名稱>.prefab 
		

		# 可調用物件相關特效（相應的損毀 \ 攻擊效果）；
		#     例如：野怪 \ 小兵 \ 炮車 \ 眼 \ 回血包 \ 砲塔\ 水晶塔；
		Object/   
			 (子資料夾內容同上)
				 
		# 場景及靜止物件特效；
		#    例如：路燈，水流，火堆，螢火蟲，蝴蝶，落葉，風沙，天氣； 			 
		Environment/            
			 (子資料夾內容同上)
			 
		# UI特效；例如：按鈕反饋，勝利界面 ，屏幕泛紅；	
		UI/
			 (子資料夾內容同上)

		# 公用狀態，公用技能；例如：Buff \ Debuff類，回血，傳送，閃現，死亡；
		State/                  
			 (子資料夾內容同上)		
			 

	# Lobby環境下使用的資源  
	Lobby/                      
		<數字>_<英文名稱>       #  例如：019020_Hawk
		 
			Animation/
				AM_<英文名稱>.anim
				AC_<英文名稱>.controller

			Material/
				MT_<英文名稱>.mat

			Prefab/
				PF_<英文名稱>.prefab  
		  
		<數字>_<英文名稱>      #  例如：019040_Molos
			(子資料夾內容同上)
	
		Environment/           #   場景及固定物件特效；例如：英雄戰士界面環境特效
			(子資料夾內容同上)	
			 
		UI/                    #   UI特效 ；例如：按鈕反饋，勝利界面
			(子資料夾內容同上)
			 
			 
			 
			 #  特效資源命名規則，詳見：
			 #  http:# bzbfzconfluence.iggcn.com/display/VoH/VFX+Asset+Naming+Convention
			 
			 
			 
其他资源存放说明：
			 
Shader/      #   Shader档根據製作人姓名來存放
	<製作人員>/      #  例如：TJ
		Effect/      #  特效類 Shader
			<英文名稱>.shader    #  例如：TJ_Particle_Dissolve.shader

Script/      #   Script 档根據製作人姓名來存放
	<製作人員> /     #  例如：Xueyuan
		Effect/      #  特效類 Script
			<英文名稱>.cs  #  例如： ScrollUV2.cs
			 
			 

	



