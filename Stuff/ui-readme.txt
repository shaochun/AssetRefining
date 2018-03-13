# --------------------------------
# - 所有的UI档案放这儿.
# --------------------------------

# -----------------------------------------
# UI 会分成 
# 
#    Ingame  - 游戏内用 UI
#    Loading - 游戏初始载入画面用 UI
#    Lobby   - 选角大厅UI
#    Setting - 选项UI
#    Misc    - 其它 (高宫望 etc)
# -----------------------------------------

# -------------------------------------------------------------------
# Prefab, Sprite 是基础子文件夹.
# 若贴图指定为 Sprite 就放入 Sprite/, 否则放入 Texture/ (自行建立).
# -------------------------------------------------------------------


UI/Common/
    Sprite/ (選擇性存在)
    HeroIcon/
    	Sprite/


UI/Ingame/

    Common/
        Animation/ (選擇性存在)
        Sprite/    (選擇性存在)
            skill_Frame.png       

    Battle/
        Animation/
        Prefab/
        Sprite/

    Buff/
        Prefab/
        Sprite/

    DeadNotice/
        Prefab/
        Sprite/

    Joystick/
        Prefab/
        Sprite/

    MiniMap/
        MaskTest/
        Prefab/
            Entry/
            Icon/
            Misc/
        Sprite/

    Skill/
        Prefab/
        Sprite/
            TX_<角色名稱>_skill_*.*    #註: 1st*: 01~04 , 2nd*: extension
                                       #例: TX_Molos_skill01.png

    StatusSystem/
        Prefab/
        Sprite/

UI/Loading/

    Prefab/
    Sprite/


UI/Lobby/

    BigIcon/
        Sprite/

    HeroSelection/
        Sprite/

    SkillIcon/
        Sprite/


UI/Setting/

    Prefab/
    Sprite/

# 真的不知如何分類, 暫代資源的UI放這裡.
UI/Misc/

    Prefab/
    Sprite/