# Reimplementing Chem Spray Infantry in Command & Conquer: Tiberian Sun
### By downloading the files from this repository and adding them to Tiberian Sun's game folder you can reimplement this forgotten unit. The unit's sprites are from the game files, however, its weapon and weapon sprites were custom made by me since there is no unused weapon for it.  
![Preview](https://private-user-images.githubusercontent.com/195215991/481415941-45fcb3c1-ae07-4396-82e5-cfb52cd0153c.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTYwNzU0MDgsIm5iZiI6MTc1NjA3NTEwOCwicGF0aCI6Ii8xOTUyMTU5OTEvNDgxNDE1OTQxLTQ1ZmNiM2MxLWFlMDctNDM5Ni04MmU1LWNmYjUyY2QwMTUzYy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwODI0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDgyNFQyMjM4MjhaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT03MjRkNGYyYmU2YjIyMzZhYWE5NmU2NWZhNTRmYmU0MWY2YzFiMTc2MjE0NTVjNTQ5NTA0NGIwOTRmOWM1ZmQzJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.nbJv6LzhPbqAmfFUK6Ub5SG6pfqYz6OYgblN_oilVwQ)

## Instructions

1. Download this repository.
2. Extract the contents from the .zip file and copy its contents.
3. Find your Tiberian Sun game folder and paste the copied files into it.  

   If you're using the Steam version, you can find Tiberian Sun in your Steam library, right-click its name, then go to Properties -> Installed Files -> Browse.  
   <br>
   If you're using the free version of Tiberian Sun, it is probably located in your C: drive under the Westwood -> SUN folder.

5. Boot up the game.

## Explanations

### I covered this cut unit [in this video](https://www.youtube.com/watch?v=jN7dCn8Xww8)

[![Watch the video](https://private-user-images.githubusercontent.com/195215991/481416297-9a504d8f-7b91-4358-94b7-3d898020ad36.PNG?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTYwNzU4NjMsIm5iZiI6MTc1NjA3NTU2MywicGF0aCI6Ii8xOTUyMTU5OTEvNDgxNDE2Mjk3LTlhNTA0ZDhmLTdiOTEtNDM1OC05NGI3LTNkODk4MDIwYWQzNi5QTkc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwODI0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDgyNFQyMjQ2MDNaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1kZjcwYWFkMGU4MDhkNTg5MGUzYWRlOTVjOGFiYTZlM2M5MWIxN2JlOGYxZWEwZmY1ZTliZDVmYWMxZDJhZTc4JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.TfoQNAw8_FHhI8VWMgLMHwHJ5ybDqiexfyYtWGOma6I)](https://www.youtube.com/watch?v=jN7dCn8Xww8)

<br>

### And I covered how you can make this mod yourself [in this video](https://youtu.be/qbcJH3iQ5fs)

[![Watch the video](https://private-user-images.githubusercontent.com/195215991/481417450-0bed52eb-835f-402b-81ae-fadf688787e0.PNG?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTYwNzcyNDIsIm5iZiI6MTc1NjA3Njk0MiwicGF0aCI6Ii8xOTUyMTU5OTEvNDgxNDE3NDUwLTBiZWQ1MmViLTgzNWYtNDAyYi04MWFlLWZhZGY2ODg3ODdlMC5QTkc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwODI0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDgyNFQyMzA5MDJaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT01ZTc4YWIwZmFiMWNhZTMwNWJhOTRkYmVlNGY4NTc1YWM0ZDAyM2UzYTRmZWRhODk5NDFiYTkxYmVkY2FhNTVjJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.L36vvl5KFursrPfnUjuh-RkhtUVrFBBNVxGslURFBOQ)](https://youtu.be/qbcJH3iQ5fs)
