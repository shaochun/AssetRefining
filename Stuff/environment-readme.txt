---------------------------------------------------------------------------------
- Envivonment 下照理會再分不同的戰鬥場景, 如 IngameScene01, IngameScene02, ...
- 但因現在我們只有一個場景, 所以簡化先不區分 子文件夾.
---------------------------------------------------------------------------------

Environment/
	所有的場景相關檔案放這兒.

	Environment/Animation

	Environment/FBX

		SK_<英文名稱>_*.FBX
		SM_<英文名稱>_*.FBX


	Environment/Lightmap

		焙烘好的 Lightmap 會放這裡. 子文件夾的命名和場景檔(.unity)相同.

	Environment/Material

		MT_<英文名稱>_*.mat

	Environment/Prefab

		<英文名稱>_*.prefab

	Environment/Texture

		TX_<英文名稱>_*.*    (1st*: Prefix, 2nd*: extension)



	Environment/Prefab/<數字>_<英文名稱>/

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
		

	Environment/Animation

	Environment/Animation

	Environment/Animation

	Environment/Animation



	Environment/Prefab/

		所有的 Prefab 放這兒.

		命名規則: <數字>.prefab


