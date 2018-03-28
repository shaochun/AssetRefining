#!/bin/bash

# -------------------------------------
# - 所有的角色和武器相關档案放这儿.
# -------------------------------------

Character/
    文件夹命名规则: <数字>_<英文名称>  #例: 010000_HouYi
        <数字>: 来自策划命名


# 放非美术定义的资源
Character/Base/
    Animator/
    Prefab/

Character/<数字>_<英文名称>/

    #let <数字>     = "010000";
    #let <英文名称> = "HouYi";
    #let <皮肤编号> = 000 ~ 999; （第一碼充當類型 如身體為0 武器為1）

    会有四个子文件夹: (资料夹一律用单数命名)

        Animation/
            AC_<英文名称>_Animation_<皮肤编号>.controller
            AC_<英文名称>_Animation_<皮肤编号>.overController 

        Fbx/
            SK_<英文名称>_<皮肤编号>.Fbx

        Material/
            MT_<英文名称>_<皮肤编号>_*.mat #注：後面_*可有可無

        Texture/
            TX_<英文名称>_<皮肤编号>_*.*           #注: 1st*: Texture type suffix (albedo, normal...)可有可無, 2nd*: extension
    
        # 所有的 Prefab 放这儿.
        Prefab/

            命名规则: <数字>_<皮肤编号>.prefab