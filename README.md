# Project Z-Defense
<img width="769" height="140" alt="Image" src="https://github.com/user-attachments/assets/56e816cc-05c3-4adf-95bb-e5b6cde74d45" />  

<br><br>
  
## 프로젝트 개요
- **개발 기간:** 2026.2.12 - 2026.3.3
- **개발 인원:** 1명  
- **장르:** 2D 탑뷰 슈팅 게임  
- **플랫폼:** PC(Windows)  
- **개발 툴:** Unity 2026
- **형상 관리:** Git/GitHub

<br>

## 게임 소개
- **오래 살아남기**  
  좀비들은 플래이어를 향해 다가옵니다.  
  플레이어는 샷건을 사용하여 스스로를 보호하며 버텨야 합니다.  
  <br>  
- **근거리/원거리 공격**  
  플레이어는 샷건을 휘둘러 근거리 공격을 하거나 샷건을 발사하여 원거리 공격을 하여 상황에 따라 적절한 공격 방식을 선택해야 합니다.  
  <br>  
- **업그레이드**  
  웨이브를 클리어하면 플레이어는 5가지 능력치 중 하나를 선택하여 업그레이드 할 수 있습니다.

<br>

## 주요 요소 소개
- **좀비**  
  본 게임에서 플레이어가 방어해야하는 몬스터입니다. 총 3가지의 좀비가 스폰되며, 웨이브가 증가할수록 강해집니다.    
  <br>  
- **플레이어**  
  플레이어블 캐릭터로, 샷건을 사용해 좀비들로부터 스스로를 지켜야 합니다.
  <br>  

<br>

## 주요 스크린샷
<p>
<img width="75%" alt="Image" src="https://github.com/user-attachments/assets/2e81daa2-0545-4d5d-a467-088188f86fa6" />
<img width="75%" alt="Image" src="https://github.com/user-attachments/assets/5c7856e1-9daa-423e-b637-5da8833f62e4" />
<img width="75%" alt="Image" src="https://github.com/user-attachments/assets/66619ca3-3b70-404f-9216-bdf7d78bbce9" />
<img width="75%" alt="Image" src="https://github.com/user-attachments/assets/b766a92b-f07d-48c3-9686-b8909cb56f8c" />

<br><br>

## 주요 소스 코드
| 항목 | 소스 코드 |
| --- | --- |
| Player | [Player.cs](./Assets/1_Objects/Player/Player.cs)<br>[NearAttackBound.cs](./Assets/1_Objects/Player/NearAttackBound.cs) |
| Shotgun | [Shotgun.cs](./Assets/1_Objects/Weapon/Shotguns/Shotgun.cs)<br>[St_PelletManager.cs](./Assets/2_Utils/St_PelletManager.cs)<br>[Pellet.cs](./Assets/1_Objects/Etc/Pellet/Pellet.cs) |
| Zombie | [Zombie.cs](./Assets/1_Objects/Monster/Zombie/Zombie.cs)<br>[Monster.cs](./Assets/1_Objects/Monster/Monster.cs) | 
| Item | [Item.cs](./Assets/1_Objects/Etc/Item/Item.cs)<br>[ItemIndicator.cs](./Assets/1_Objects/Etc/Item/ItemIndicator.cs)<br>[AmmoItem.cs](./Assets/1_Objects/Etc/Item/AmmoItem/AmmoItem.cs)<br>[HealthItem.cs](./Assets/1_Objects/Etc/Item/HealthItem/HealthItem.cs) |
| Upgrade System | [St_LevelManager.cs](./Assets/2_Utils/St_LevelManager.cs) |
| Game Manager | [St_GameManager.cs](./Assets/2_Utils/St_GameManager.cs) |
| Monster Generator | [St_MonsterGenerator.cs](./Assets/2_Utils/St_MonsterGenerator.cs) |
| Camera Controller | [St_CameraController.cs](./Assets/2_Utils/St_CameraController.cs) |
| UI | [St_BulletCountIndicator.cs](./Assets/3_UI/InGameUI/St_BulletCountIndicator.cs)<br>[St_HPIndicator.cs](./Assets/3_UI/InGameUI/St_HPIndicator.cs)<br>[St_ReloadIndicator.cs](./Assets/3_UI/InGameUI/St_ReloadIndicator.cs)<br>[St_RoundIndicator.cs](./Assets/3_UI/InGameUI/St_RoundIndicator.cs) | 

<br>

## 프로젝트 스크립트 트리  
* 에셋 및 라이브러리 스크립트는 포함되어있지 않습니다.
* 본 프로젝트에서는 유료 에셋이 사용되지 않았습니다.

  * 📁 [1_Objects](./Assets/1_Objects)
  * 📁 [Etc](./Assets/1_Objects/Etc)
    * 📁 [BloodExplode](./Assets/1_Objects/Etc/BloodExplode)
      * 📄 [BloodExplode.cs](./Assets/1_Objects/Etc/BloodExplode/BloodExplode.cs)
    * 📁 [BloodStain](./Assets/1_Objects/Etc/BloodStain)
      * 📄 [BloodStain.cs](./Assets/1_Objects/Etc/BloodStain/BloodStain.cs)
    * 📁 [Item](./Assets/1_Objects/Etc/Item)
      * 📁 [AmmoItem](./Assets/1_Objects/Etc/Item/AmmoItem)
        * 📄 [AmmoItem.cs](./Assets/1_Objects/Etc/Item/AmmoItem/AmmoItem.cs)
      * 📁 [HealthItem](./Assets/1_Objects/Etc/Item/HealthItem)
        * 📄 [HealthItem.cs](./Assets/1_Objects/Etc/Item/HealthItem/HealthItem.cs)
      * 📄 [Item.cs](./Assets/1_Objects/Etc/Item/Item.cs)
      * 📄 [ItemIndicator.cs](./Assets/1_Objects/Etc/Item/ItemIndicator.cs)
    * 📁 [MuzzleFire](./Assets/1_Objects/Etc/MuzzleFire)
      * 📄 [MuzzleFire.cs](./Assets/1_Objects/Etc/MuzzleFire/MuzzleFire.cs)
    * 📁 [Pellet](./Assets/1_Objects/Etc/Pellet)
      * 📄 [Pellet.cs](./Assets/1_Objects/Etc/Pellet/Pellet.cs)
  * 📁 [Monster](./Assets/1_Objects/Monster)
    * 📁 [Zombie](./Assets/1_Objects/Monster/Zombie)
      * 📄 [Zombie.cs](./Assets/1_Objects/Monster/Zombie/Zombie.cs)
    * 📄 [Monster.cs](./Assets/1_Objects/Monster/Monster.cs)
  * 📁 [Player](./Assets/1_Objects/Player)
    * 📄 [NearAttackBound.cs](./Assets/1_Objects/Player/NearAttackBound.cs)
    * 📄 [Player.cs](./Assets/1_Objects/Player/Player.cs)
    * 📄 [PlayerLeg.cs](./Assets/1_Objects/Player/PlayerLeg.cs)
    * 📄 [Reticle.cs](./Assets/1_Objects/Player/Reticle.cs)
  * 📁 [Weapon](./Assets/1_Objects/Weapon)
    * 📁 [Shotguns](./Assets/1_Objects/Weapon/Shotguns)
      * 📄 [M1897.cs](./Assets/1_Objects/Weapon/Shotguns/M1897.cs)
      * 📄 [Shotgun.cs](./Assets/1_Objects/Weapon/Shotguns/Shotgun.cs)
* 📁 [2_Utils](./Assets/2_Utils)
  * 📄 [DataManager.cs](./Assets/2_Utils/DataManager.cs)
  * 📄 [Math_.cs](./Assets/2_Utils/Math_.cs)
  * 📄 [MatrixTransform.cs](./Assets/2_Utils/MatrixTransform.cs)
  * 📄 [Range_.cs](./Assets/2_Utils/Range_.cs)
  * 📄 [ScreenCenterLine.cs](./Assets/2_Utils/ScreenCenterLine.cs)
  * 📄 [St_CameraController.cs](./Assets/2_Utils/St_CameraController.cs)
  * 📄 [St_GameManager.cs](./Assets/2_Utils/St_GameManager.cs)
  * 📄 [St_LevelManager.cs](./Assets/2_Utils/St_LevelManager.cs)
  * 📄 [St_MonsterGenerator.cs](./Assets/2_Utils/St_MonsterGenerator.cs)
  * 📄 [St_MouseManager.cs](./Assets/2_Utils/St_MouseManager.cs)
  * 📄 [St_ObjectManager.cs](./Assets/2_Utils/St_ObjectManager.cs)
  * 📄 [St_PelletManager.cs](./Assets/2_Utils/St_PelletManager.cs)
  * 📄 [St_SoundPlayer.cs](./Assets/2_Utils/St_SoundPlayer.cs)
  * 📄 [St_UpdateManager.cs](./Assets/2_Utils/St_UpdateManager.cs)
* 📁 [3_UI](./Assets/3_UI)
  * 📁 [Buttons](./Assets/3_UI/Buttons)
    * 📄 [DataResetButton.cs](./Assets/3_UI/Buttons/DataResetButton.cs)
    * 📄 [ExitButton.cs](./Assets/3_UI/Buttons/ExitButton.cs)
    * 📄 [RestartButton.cs](./Assets/3_UI/Buttons/RestartButton.cs)
    * 📄 [ResumeButton.cs](./Assets/3_UI/Buttons/ResumeButton.cs)
    * 📄 [StartButton.cs](./Assets/3_UI/Buttons/StartButton.cs)
    * 📄 [TitleButton.cs](./Assets/3_UI/Buttons/TitleButton.cs)
  * 📁 [GameOverUI](./Assets/3_UI/GameOverUI)
    * 📄 [GameOverUI.cs](./Assets/3_UI/GameOverUI/GameOverUI.cs)
    * 📄 [ResultText.cs](./Assets/3_UI/GameOverUI/ResultText.cs)
    * 📄 [UIIcon.cs](./Assets/3_UI/GameOverUI/UIIcon.cs)
  * 📁 [InGameUI](./Assets/3_UI/InGameUI)
    * 📄 [HitIndicator.cs](./Assets/3_UI/InGameUI/HitIndicator.cs)
    * 📄 [St_BulletCountIndicator.cs](./Assets/3_UI/InGameUI/St_BulletCountIndicator.cs)
    * 📄 [St_DamageIndicator.cs](./Assets/3_UI/InGameUI/St_DamageIndicator.cs)
    * 📄 [St_HPIndicator.cs](./Assets/3_UI/InGameUI/St_HPIndicator.cs)
    * 📄 [St_InGameUI.cs](./Assets/3_UI/InGameUI/St_InGameUI.cs)
    * 📄 [St_RecoveryIndicator.cs](./Assets/3_UI/InGameUI/St_RecoveryIndicator.cs)
    * 📄 [St_ReloadIndicator.cs](./Assets/3_UI/InGameUI/St_ReloadIndicator.cs)
    * 📄 [St_RemainEnemyIndicator.cs](./Assets/3_UI/InGameUI/St_RemainEnemyIndicator.cs)
    * 📄 [St_RoundIndicator.cs](./Assets/3_UI/InGameUI/St_RoundIndicator.cs)
  * 📁 [PauseUI](./Assets/3_UI/PauseUI)
    * 📄 [PauseUI.cs](./Assets/3_UI/PauseUI/PauseUI.cs)
  * 📁 [RoundStartUI](./Assets/3_UI/RoundStartUI)
    * 📄 [RoundStartUI.cs](./Assets/3_UI/RoundStartUI/RoundStartUI.cs)
  * 📁 [TitleUI](./Assets/3_UI/TitleUI)
    * 📄 [BestRoundsText.cs](./Assets/3_UI/TitleUI/BestRoundsText.cs)
  * 📁 [UpgradeUI](./Assets/3_UI/UpgradeUI)
    * 📄 [UpgradeButton.cs](./Assets/3_UI/UpgradeUI/UpgradeButton.cs)
    * 📄 [UpgradeItem.cs](./Assets/3_UI/UpgradeUI/UpgradeItem.cs)
    * 📄 [UpgradeText.cs](./Assets/3_UI/UpgradeUI/UpgradeText.cs)
    * 📄 [UpgradeUI.cs](./Assets/3_UI/UpgradeUI/UpgradeUI.cs)
  * 📄 [IconAnimation.cs](./Assets/3_UI/IconAnimation.cs)
  * 📄 [ScreenSwitcher.cs](./Assets/3_UI/ScreenSwitcher.cs)
