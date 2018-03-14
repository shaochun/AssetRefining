#!/bin/bash

# -------------------------------------
# - 所有的角色和武器相關档案放这儿.
# -------------------------------------

Lobby/Character/
    文件夹命名规则: <数字>_<英文名称>  #例: 010000_HouYi
        <数字>: 来自策划命名


# 放非美術定義的資源
Lobby/Character/Base/
    Animator/
    Prefab/

Lobby/Character/<数字>_<英文名称>/

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
            TX_<英文名称>_<皮膚編號>_*.*           #註: 1st*: Texture type suffix (albedo, normal...), 2nd*: extension
            TX_<英文名称>_Weapon_<皮膚編號>_*.*    #註: 1st*: Texture type suffix (albedo, normal...), 2nd*: extension
    
        # 所有的 Prefab 放这儿.
        Prefab/

            命名规则: <英文名称>_<皮膚編號>.prefab
                      <英文名称>_Weapon_<皮膚編號>.prefab

文件夹 PATH 列表
卷序列号为 0002-3DA7
D:.
│  
├─Character
│  │  019020_Hawk.meta
│  │  019030_Lilith.meta
│  │  019040_Molos.meta
│  │  
│  ├─019020_Hawk
│  │  │  Animation.meta
│  │  │  FBX.meta
│  │  │  Material.meta
│  │  │  Prefab.meta
│  │  │  Texture.meta
│  │  │  
│  │  ├─Animation
│  │  │      AC_Hawk_Animation_00.overrideController
│  │  │      AC_Hawk_Animation_00.overrideController.meta
│  │  │      
│  │  ├─FBX
│  │  │      SK_Hawk_00.FBX
│  │  │      SK_Hawk_00.FBX.meta
│  │  │      
│  │  ├─Material
│  │  │      MT_Hawk_00.mat
│  │  │      MT_Hawk_00.mat.meta
│  │  │      MT_Hawk_ver4.4_00.mat
│  │  │      MT_Hawk_ver4.4_00.mat.meta
│  │  │      
│  │  ├─Prefab
│  │  │      Hawk_00.prefab
│  │  │      Hawk_00.prefab.meta
│  │  │      
│  │  └─Texture
│  │          TX_Hawk_00_albodo.tga
│  │          TX_Hawk_00_albodo.tga.meta
│  │          TX_Hawk_00_emission.tga
│  │          TX_Hawk_00_emission.tga.meta
│  │          TX_Hawk_00_hairDetail.tga
│  │          TX_Hawk_00_hairDetail.tga.meta
│  │          TX_Hawk_00_mask.tga
│  │          TX_Hawk_00_mask.tga.meta
│  │          TX_Hawk_00_MSTG.tga
│  │          TX_Hawk_00_MSTG.tga.meta
│  │          TX_Hawk_00_normal.tga
│  │          TX_Hawk_00_normal.tga.meta
│  │          TX_Hawk_00_reflection.tga
│  │          TX_Hawk_00_reflection.tga.meta
│  │          TX_Hawk_00_RREH.tga
│  │          TX_Hawk_00_RREH.tga.meta
│  │          TX_Hawk_00_skin_thickness.tga
│  │          TX_Hawk_00_skin_thickness.tga.meta
│  │          
│  ├─019030_Lilith
│  │  │  Animation.meta
│  │  │  FBX.meta
│  │  │  Material.meta
│  │  │  Prefab.meta
│  │  │  Texture.meta
│  │  │  
│  │  ├─Animation
│  │  │      AC_Lilith_Animation_00.overrideController
│  │  │      AC_Lilith_Animation_00.overrideController.meta
│  │  │      
│  │  ├─FBX
│  │  │      SK_Lilith_00.FBX
│  │  │      SK_Lilith_00.FBX.meta
│  │  │      
│  │  ├─Material
│  │  │      MT_Lilith_00.mat
│  │  │      MT_Lilith_00.mat.meta
│  │  │      
│  │  ├─Prefab
│  │  │      Lilith_00.prefab
│  │  │      Lilith_00.prefab.meta
│  │  │      
│  │  └─Texture
│  │          TX_lilith_00_albedo.tga
│  │          TX_lilith_00_albedo.tga.meta
│  │          TX_lilith_00_albedo1.png
│  │          TX_lilith_00_albedo1.png.meta
│  │          TX_lilith_00_emission.png
│  │          TX_lilith_00_emission.png.meta
│  │          TX_lilith_00_metallic.png
│  │          TX_lilith_00_metallic.png.meta
│  │          TX_lilith_00_normal.tga
│  │          TX_lilith_00_normal.tga.meta
│  │          TX_lilith_00_reflection.png
│  │          TX_lilith_00_reflection.png.meta
│  │          TX_lilith_00_thickness.png
│  │          TX_lilith_00_thickness.png.meta
│  │          
│  └─019040_Molos
│      │  Animation.meta
│      │  FBX.meta
│      │  Material.meta
│      │  Prefab.meta
│      │  Texture.meta
│      │  
│      ├─Animation
│      │      AC_Molos_Animation_00.overrideController
│      │      AC_Molos_Animation_00.overrideController.meta
│      │      
│      ├─FBX
│      │      SK_Molos_00.FBX
│      │      SK_Molos_00.FBX.meta
│      │      
│      ├─Material
│      │      MT_Molos_00.mat
│      │      MT_Molos_00.mat.meta
│      │      
│      ├─Prefab
│      │      Molos_00.prefab
│      │      Molos_00.prefab.meta
│      │      
│      └─Texture
│              TX_Molos_00_albedo.tga
│              TX_Molos_00_albedo.tga.meta
│              TX_Molos_00_emission.tga
│              TX_Molos_00_emission.tga.meta
│              TX_Molos_00_GLOSS.tga
│              TX_Molos_00_GLOSS.tga.meta
│              TX_Molos_00_metallicness.tga
│              TX_Molos_00_metallicness.tga.meta
│              TX_Molos_00_normal.tga
│              TX_Molos_00_normal.tga.meta
│              
├─Common
│  │  Animation.meta
│  │  Texture.meta
│  │  
│  ├─Animation
│  │      lobby_camera.anim
│  │      lobby_camera.anim.meta
│  │      Lobby_Camera.controller
│  │      Lobby_Camera.controller.meta
│  │      Lobby_character.controller
│  │      Lobby_character.controller.meta
│  │      
│  └─Texture
│          reflection.jpg
│          reflection.jpg.meta
│          
└─Scene
    │  Material.meta
    │  Texture.meta
    │  
    ├─Material
    │      MT_CalibrationFloorSpecularGloss.mat
    │      MT_CalibrationFloorSpecularGloss.mat.meta
    │      
    └─Texture
            TX_CalibrationFloorSpecularGloss.tif
            TX_CalibrationFloorSpecularGloss.tif.meta
            
