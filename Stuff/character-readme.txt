# -------------------------------------
# - 所有的角色和武器相關档案放这儿.
# -------------------------------------

Character/
	文件夹命名规则: <数字>_<英文名称>  #例: 010000_HouYi
		<数字>: 来自策划命名
	

	Character/<数字>_<英文名称>/

		#let <数字>     = "010000";
	    #let <英文名称> = "HouYi";
	    #let <皮膚編號> = 00 ~ 99;

		会有四个子文件夹: (资料夹一律用单数命名)

			Animation/
				AC_<英文名称>_Animation_<皮膚編號>.controller
				AC_<英文名称>_Animation_<皮膚編號>.overController 
				# (武器動作(Weapon)會和角色動作做在一起.

			FBX/
				SK_<英文名称>_<皮膚編號>.FBX
				SK_<英文名称>_Weapon_<皮膚編號>_*.mat

			Material/
				MT_<英文名称>_<皮膚編號>_*.mat
				MT_<英文名称>_Weapon_<皮膚編號>_*.mat

			Texture/
				TX_<英文名称>_<皮膚編號>_*.*           #註: 1st*: Prefix, 2nd*: extension
				TX_<英文名称>_Weapon_<皮膚編號>_*.*    #註: 1st*: Prefix, 2nd*: extension
		
			# 所有的 Prefab 放这儿.
			Prefab/

				命名规则: <英文名称>_<皮膚編號>.prefab
						  <英文名称>_Weapon_<皮膚編號>.prefab