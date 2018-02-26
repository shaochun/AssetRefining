# --------------------------------
# - 所有的角色档案放这儿.
# --------------------------------

Character/
	文件夹命名规则: <数字>_<英文名称>  #例: 010000_HouYi
		<数字>: 来自策划命名
	

	Character/Prefab/<数字>_<英文名称>/

		#let <数字>     = "010000";
	    #let <英文名称> = "HouYi";

		会有四个子文件夹: (资料夹一律用单数命名)

			Animation/
				AC_<英文名称>_Animation.controller
				AC_<英文名称>_Animation.overController 

			FBX/
				SK_<英文名称>.FBX

			Material/
				MT_<英文名称>_*.mat

			Texture/
				TX_<英文名称>_*.*    #註: 1st*: Prefix, 2nd*: extension
		

	Character/Prefab/

		所有的 Prefab 放这儿.

		命名规则: <数字>.prefab