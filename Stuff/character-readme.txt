Character/
	所有的角色檔案放這兒.
	文件夾命名規則: <數字>_<英文名稱> (例: 010000_HouYi)

		<數字>: 來自策劃命名
	

	Character/Prefab/<數字>_<英文名稱>/

		let <數字>     = "010000";
	    let <英文名稱> = "HouYi";

		會有四個子文件夾: (資料夾一律用單數命名)

			Animation/
				AC_<英文名稱>_Animation.controller
				AC_<英文名稱>_Animation.overController 

			FBX/
				SK_<英文名稱>.FBX

			Material/
				MT_<英文名稱>_*.mat

			Texture/
				TX_<英文名稱>_*.*    (1st*: Prefix, 2nd*: extension)
		

	Character/Prefab/

		所有的 Prefab 放這兒.

		命名規則: <數字>.prefab


