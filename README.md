# Bookmarks
1. [Initial setup](#Initial-Setup)<br />
2. [Add a new ship](#How-to-add-a-new-ship)<br />
3. [Add a new loadout](#How-to-add-a-loadout)<br />
4. [Initial Ellydium setup](#Initial-Ellydium-setup)<br />
5. [Ellydium ship loadout](#How-to-add-an-Ellydium-loadout)<br />


## Important changes: 
- The "Unequip 1" and Unequip 2" coordinates have been removed and replaced by a screenshot. If the "unequip" function isn't working, then please take a screenshot of the "Remove all modules"
button by yourself and place it in the Settings folder with the name "Remove_all_module.png"
  


<details>
<summary>Screenshot</summary>
  
![Remove_all_module](https://github.com/user-attachments/assets/9b0ff1bc-5f9b-4397-a08d-7de67c913b44)

![image](https://github.com/user-attachments/assets/cfc7e256-e661-45b7-8a1c-055492a7992f)
</details>
- The folder and file structure has changed. It is now:

![image](https://github.com/user-attachments/assets/6a77b517-ddae-4f96-92bb-207b55600594)


<details>
<summary>Initial Setup</summary>
  Prerequisites: AHK v1.1<br />
  <br />
  1. Download the repository.<br /><br />
  2. Unpack the zip in a folder.<br /><br />
  3. Run the script.<br /><br />
  4. Add the missing coordinates.<br /><br />
  5. Start with the 5 factions (Empire, Federation, Jericho, Ellydium and Unique).<br />
  <details>
  <summary>Screenshot</summary>
    
  ![20250514_16 05 24](https://github.com/user-attachments/assets/804ef00b-9a71-44b6-9c14-d9548b1d3627)
  </details>
  6. Set the "Scroll" coodinates somewhere at the ship tree where no ships are. Don't place it on the scollbar.<br />
  <details>
  <summary>Screenshot</summary>

  ![20250514_16 13 03](https://github.com/user-attachments/assets/a2cd8950-bd5c-40fa-bd4e-655d60e6a51c)
  </details>
	7. Set the "Back" button coordinates by pressing esc to open the menu and then select the "Back" button.<br />
	<details>
	<summary>Screenshot</summary>
    
  ![20250514_16 16 08](https://github.com/user-attachments/assets/4a054336-be4a-433c-9a4a-c2470ccdb5ba)
	</details>
	8. Set the 4 Ship slots while the ship tree is open. They are 1,2,3,4 from left to right.<br />
	<details>
	<summary>Screenshot</summary>

  ![20250514_16 19 26](https://github.com/user-attachments/assets/0123dfee-5a5a-4a0f-a0e4-f957ddadc70b)
  </details>
  9. Set the coordinates for "Apply Ellydium". Open an Ellydium tree and click the "Apply" button at the bottom. If you have no Ellydium ships, then set the coordinates somewhere on the screen. They are only used when loading an Ellydium ship.<br />
  <details>
  <summary>Screenshot</summary>

  ![20250514_16 25 27](https://github.com/user-attachments/assets/b5c0910f-d9c9-4b4f-abc7-4e36e9279950)
  </details>
  10. Set the coordinates for Preset 1 to 4 and the "Load" button. The Loadout order is reversed in-game so Preset 1 is the most right Loadout.<br />
  <details>
  <summary>Screenshot</summary>

  ![20250514_16 27 40](https://github.com/user-attachments/assets/d53f6737-6332-4b56-89a8-3211fdf23532)
  </details>
  11. Set the coordinates for the "Yes" button after you click on the "Load" button.<br />
  <details>
  <summary>Screenshot</summary>

  ![20250514_16 30 38](https://github.com/user-attachments/assets/dc474414-c274-4251-8dd7-a28249c13841)
  </details>
  12. Set the coordinates for the 4 Crews. Click in the middle of each crew.<br />
  <details>
  <summary>Screenshot</summary>

  ![20250514_16 34 00](https://github.com/user-attachments/assets/26f94dd4-876c-4ee7-820d-e1325b09ca5f)
  </details>
  13. Set the coordinates for "Crew 1-1" and "Crew 15-3". "Crew 1-1" is the top left implant and "Crew 15-3" the bottom right.<br />
  <details>
  <summary>Screenshot</summary>
  
  ![20250514_16 36 54](https://github.com/user-attachments/assets/7469a30b-6efe-46fe-ad34-caef46d3708f)
  </details>
  14. Set the coordinates for the "Implant" button. Don't click on the text itself as it can break the color recognition of the button.<br />
  <details>
  <summary>Screenshot</summary>
  
  ![20250514_16 38 49](https://github.com/user-attachments/assets/ce84c24e-9d51-46ce-90ed-43dee92b5c9e)
  </details>
  15. Set your "Crew" keybind to "c" and your "Ships" keybind to "t"<br />
  <details>
  <summary>Screenshot</summary>
	  
  ![20250514_16 51 06](https://github.com/user-attachments/assets/b2539d7f-dac2-409a-88c0-4935a767f64e)
  </details>
</details>

<details>
<summary>Add a new ship</summary><br />
<br />
  1. Click on "Loadout" at the bottom right of the script.<br />
  <details>
  <summary>Screenshot</summary>

  ![20250516_12 01 02](https://github.com/user-attachments/assets/84beb1ed-0c48-4f85-8cff-27af81841f58)
  </details>
  2. Click the "+" sign next to the Field that shows the selected ship. It should say "None" at the beginning.<br />
  <details>
  <summary>Screenshot</summary>

  ![20250516_12 02 23](https://github.com/user-attachments/assets/bc8ad7bd-ac1a-4625-ad1b-c28893b8468f)
  </details>
  3. Enter the name of the ship, select the faction and open the ship tree.<br /><br />
  4. Now you need to set "Scroll 1" and if needed "Scroll 2". For the 3 Main trees (Empire, Federation and Jericho) you should use a number that is high enough to get from the top of the tree all the way to the bottom. This is used to zero in the tree.<br /><br />
  5. If your ship isn't visible when scrolled all the way to the bottom, then you need to set "Scroll 2" to "Up" and slowly scroll up until you reach your ship. The script counts the amount for you.<br />
  <details>
  <summary>Screenshot</summary>

  ![20250516_12 08 53](https://github.com/user-attachments/assets/50d263c0-c64c-47c7-8026-9635b005d203)
  </details>
  6. Select "Click" and click on the ship that you want to setup.<br />
  <details>
  <summary>Screenshot</summary>

  ![20250516_12 10 16](https://github.com/user-attachments/assets/91e9a100-a789-4255-a9fd-7118fa70a9ab)
  </details>
  7. Click on the "Add" button.<br /><br />
  8. Done. The ship is now added.<br />

</details>
