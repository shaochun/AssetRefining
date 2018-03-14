#!/bin/bash

# -------------------------------------
# - 放置大厅(Lobby)相关档案 
# -------------------------------------

#Lobby 角色相关档案
Lobby/Character/
    文件夹命名规则: <数字>_<英文名称>  #例: 010000_HouYi
        <数字>: 来自策划命名


# 放非美术定义的资源
Lobby/Character/Common/
    Animation/
        *.anim
        *.controller
    Texture/
        TX_*.*                        #注: 1st*: Texture name, 2nd*: extension

Lobby/Character/<数字>_<英文名称>/

    #let <数字>     = "010000";
    #let <英文名称> = "HouYi";
    #let <皮肤编号> = 00 ~ 99;

    会有四个子文件夹: (资料夹一律用单数命名)

        Animation/
            AC_<英文名称>_Animation_<皮肤编号>.controller
            AC_<英文名称>_Animation_<皮肤编号>.overController
            # (武器动作(Weapon)会和角色动作做在一起.

        FBX/
            SK_<英文名称>_<皮肤编号>.FBX
            SK_<英文名称>_Weapon_<皮肤编号>_*.mat

        Material/
            MT_<英文名称>_<皮肤编号>_*.mat
            MT_<英文名称>_Weapon_<皮肤编号>_*.mat

        Texture/
            TX_<英文名称>_<皮肤编号>_*.*           #注: 1st*: Texture type suffix (albedo, normal...), 2nd*: extension
            TX_<英文名称>_Weapon_<皮肤编号>_*.*    #注: 1st*: Texture type suffix (albedo, normal...), 2nd*: extension

        # 所有的 Prefab 放这儿.
        Prefab/

            命名规则: <英文名称>_<皮肤编号>.prefab
                      <英文名称>_Weapon_<皮肤编号>.prefab

#Lobby 场景相关档案
Lobby/Scene/
    Material/
        MT_*.mat
    Texture/
        TX_*.*           #注: 1st*: Texture name, 2nd*: extension