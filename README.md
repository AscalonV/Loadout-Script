## Important changes: 
- For the new Ellydium tree selector to work you need to name the Ellydium ships exactly like ingame:
  - Tai'Kin
  - Yith'Mor
  - Thar'Ga
  - Waz'Got
  - Drag'Thir
  - Ze'Ta
- The "Unequip 1" and Unequip 2" coordinates have been removed and replaced by a screenshot. If the "unequip" function isn't working, then please take a screenshot of the "Remove all modules"
button by yourself and place it in the Settings folder with the name "Remove_all_module.png"
<details>
<summary>Screenshot</summary>
  
![Remove_all_module](https://github.com/user-attachments/assets/9b0ff1bc-5f9b-4397-a08d-7de67c913b44)

![image](https://github.com/user-attachments/assets/cfc7e256-e661-45b7-8a1c-055492a7992f)
</details>
- The folder and file structure has changed. It is now:

![image](https://github.com/user-attachments/assets/6a77b517-ddae-4f96-92bb-207b55600594)


# Initial Setup
<details>
<summary>Initial Setup</summary><br />
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

# Add a new ship
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

# Add a new Loadout
<details>
<summary>Add a new Loadout</summary><br />
<br />
  1. Select the ship you want to add a Loadout and click on "Edit" in the "Loadouts" section.<br />
  <details>
  <summary>Screenshot</summary>
  	  
  <img width="752" height="533" alt="20250731_17 50 57" src="https://github.com/user-attachments/assets/4e68b0f2-0025-4325-a647-f265b33e4565" />
  </details>
  2. Click the "+" sign next to the Field that shows the selected Loadout. It should say "None" at the beginning.<br />
  <details>
  <summary>Screenshot</summary>
  <img width="752" height="533" alt="image" src="https://github.com/user-attachments/assets/25a52f6f-222e-4703-8c5b-0f686d2f1d30" />
  </details>
  3. Enter the name of the Loadout, select the preset the script should select in-game (from right to left 1 to 4) and add the implants for your loadout (1 is the top row, 2 is the middle row and 3 is the bottom row.<br />
  <details>
  <summary>Screenshot</summary>

  <img width="752" height="533" alt="image" src="https://github.com/user-attachments/assets/45003bec-575f-4ae4-b05b-f48323c698cf" />
  </details>
  7. Click on the "Add" button.<br /><br />
  8. Done. The new Loadout is now added.<br />
  
</details>

# How to add an Ellydium tree loadout
<details>
<summary>How to add an Ellydium tree loadout</summary><br />
<br />
  1. Download the .ini's of the Ellydium ships found in the "Builds/Ellydium" folder and place them in your Build/Ellydium folder if you haven't already. These are needed because they contain the in-game node data.<br />
  <details>
  <summary>Screenshot</summary>
  	  
  <img width="1574" height="468" alt="image" src="https://github.com/user-attachments/assets/bf6759dd-d43f-4631-ade7-0b543403388b" />
  </details>
  2. Go to "Loadouts" section where you can select a Ship<br /><br />
  3. Select an Ellydium ship and click on the "Edit" button in the "Loadouts" section<br />
  <details>
  <summary>Screenshot</summary>
  	  
  <img width="752" height="533" alt="image" src="https://github.com/user-attachments/assets/971b048b-73d3-4e16-a6cb-8f4e2336c34b" />
  </details>
  4. Click on "Setup". This needs to be done for every Ellydium ship seperately<br />
  <details>
  <summary>Screenshot</summary>
  	  
  <img width="752" height="533" alt="image" src="https://github.com/user-attachments/assets/d103cc7b-bf74-475b-87bf-f921fa48d3b2" />
  </details>
  5. Go through each node class and click the corresponding node in the Ellydium tree<br />
  <details>
  <summary>Screenshot</summary>
  	  
  <img width="777" height="727" alt="image" src="https://github.com/user-attachments/assets/be901fc2-b4b0-4d7e-9b5c-0895c4e96189" />
  </details>
  6. Set the coordinates for each node. IMPORTANT! Set the coordinates on a point of the node, that is bright green when activated and dark when deactivated. Otherwise the detection might fail.<br />
  <details>
  <summary>Screenshot</summary>
  	  
  <img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/51c945fc-ca4d-48a9-9e99-194f272bfa74" />
  </details>
  7. Now go to "Setup Node Colors"<br />
  <details>
  <summary>Screenshot</summary>
  	  
  <img width="777" height="727" alt="image" src="https://github.com/user-attachments/assets/154b05f3-eb86-4faf-8cbf-9540af9927f8" />
  </details>
  8. Now you have to select a node that is on and off and a spec mod that is on and off to save the color-code of the state. It is best to choose a node thatis completely filled like a shield node.<br />
  <details>
  <summary>Screenshot</summary>
  	  
  <img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/8c7ea06c-8d29-4121-b349-b179659c55fa" />
  </details>
  9. Now use the "Check Nodes" function to see if there are nodes that aren't detected correctly and redo the coordiantes for them.<br />
  <details>
  <summary>Screenshot</summary>
  	  
  <img width="777" height="727" alt="image" src="https://github.com/user-attachments/assets/19f7739b-55ba-4482-9851-c6413fa565c9" />
  </details>
  10. If all nodes work, then you have finished the setup for this ship. It is possible, that the nodes still fail to activate, when the script is used, even if the "Check Nodes" function detected all. In this case, just set the coordinates for the failed node again.<br />
  <details>
  <summary>Screenshot</summary>
  	  
  <img width="777" height="727" alt="image" src="https://github.com/user-attachments/assets/9b10b894-fa9b-4d05-b818-c3dbae48d421" />
  </details>
