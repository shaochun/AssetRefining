# -----------------------------------------
# UI 会分成 
# 
#    Ingame  - 游戏内用 UI
#    Loading - 游戏初始载入画面用 UI
#    Lobby   - 选角大厅UI
#    Setting - 选项UI
#    Misc    - 其它 (高宫望 etc)
# -----------------------------------------

Prefab, Sprite 是基礎子文件夹.
若贴图指定为 Sprite 就放入 Sprite/, 否则放入 Texture/ (自行建立).

# --------------------------------
# - 所有的UI档案放这儿.
# --------------------------------
UI/Ingame/

    Battle/
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
        Sprite/

    SkillIcon/
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


UI/Misc/

    Animation/
        *.anim 档放这里.

    Common/
        # 共用贴图放这里.
        Sprite/

    Skill/

        ?

    Sprite/

        ?

    StatusSystem/

        Prefab/