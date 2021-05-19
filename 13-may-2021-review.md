# Canopy UI Review

**Global**

  ---
  1. Body Font Size should be:
  
       `14px`
       
 ---     
  2. Button height should be:
  
      `44px`
      
  ---    
  3. Tag should be:   
  
      `border-radius: 22px; padding: 3px 8px; height: 32px;`

       BEFORE:
       <img width="988" alt="Screen Shot 2021-05-13 at 3 56 31 PM" src="https://user-images.githubusercontent.com/6618158/118096653-3959fe00-b404-11eb-9d93-599648a29168.png">
       
       AFTER:
       
       <img width="651" alt="Screen Shot 2021-05-19 at 5 44 55 PM" src="https://user-images.githubusercontent.com/6618158/118792124-eed7f600-b8c9-11eb-8f8c-4137268c4862.png">
  ---
  4. Input text should be: 
  
      `height: 40px`
      
  ---    
  5. Close icon for modal should be: 
  
      https://github.com/markbanaria/canopy-design/blob/master/assets/close.svg
      
  ---    
  8. File widget should be:

     CSS: https://github.com/markbanaria/canopy-design/blob/master/css/file-widget.css
     
     HTML:
     
     ```
      <div class="file-widget">
        <img src="assets/file-excel.svg">
        filename.exe
      </div>
     ```
     RESULT:
     <img width="1071" alt="Screen Shot 2021-05-19 at 5 48 54 PM" src="https://user-images.githubusercontent.com/6618158/118792733-85a4b280-b8ca-11eb-8224-98bde720cc33.png">
     
     FILES:
     
     excel https://github.com/markbanaria/canopy-design/blob/master/assets/file-word-black.svg
     
     word https://github.com/markbanaria/canopy-design/blob/master/assets/file-excel-black.svg
     
     image https://github.com/markbanaria/canopy-design/blob/master/assets/file-jpg-black.svg
     
     pdf https://github.com/markbanaria/canopy-design/blob/master/assets/file-pdf-black.svg
     


  ____
  9. Table should have border 

     Border around the header: `1ps solid #dcdcdc`
     
     td font size: `12px`
     
     thumbnail size: `20px`
     
     check-icon size: `16px`
     
     progress bar height: `8px`
     
     striped row should have `border: none`

     BEFORE:
     
     <img width="711" alt="Screen Shot 2021-05-19 at 6 15 25 PM" src="https://user-images.githubusercontent.com/6618158/118796561-4d06d800-b8ce-11eb-916f-968d4aa67462.png">

     
     AFTER:
     
     <img width="803" alt="Screen Shot 2021-05-19 at 6 16 34 PM" src="https://user-images.githubusercontent.com/6618158/118796613-598b3080-b8ce-11eb-864f-140b9830ef67.png">

  ---

  10. Navigation shoud have Arrow down across the client item 

      BEFORE:
      
      <img width="251" alt="Screen Shot 2021-05-19 at 6 20 30 PM" src="https://user-images.githubusercontent.com/6618158/118797267-fea60900-b8ce-11eb-91a6-3a1ca6007f9d.png">

      AFTER:
      
      <img width="393" alt="Screen Shot 2021-05-19 at 6 20 43 PM" src="https://user-images.githubusercontent.com/6618158/118797249-f8b02800-b8ce-11eb-806e-08a2aacbfd59.png">


  ---

**Dashboard**

  1. Icon for download should be:

     https://github.com/markbanaria/canopy-design/blob/master/assets/cloud-download.svg
     
  ---   
  2. Remove Capitalization: Employees, Contractors -- DONE

  ---   
 
  3. Table should have table-striped -- DONE
  ---
  4. Font styling on table body should be — 
  
       For clickable: `bold, use #202020` 
       
       For non-clickable: `remove bold, use #727272`
       
       BEFORE:
       
       <img width="1413" alt="Screen Shot 2021-05-19 at 10 03 29 PM" src="https://user-images.githubusercontent.com/6618158/118826425-117c0600-b8ee-11eb-8763-a5fc43aba9b2.png">

       
       AFTER:
       
       <img width="604" alt="Screen Shot 2021-05-19 at 10 03 54 PM" src="https://user-images.githubusercontent.com/6618158/118826487-1e005e80-b8ee-11eb-8e28-c679a97d37f4.png">

  ---     
  5. Progress bar-sizing should be 

     `height: 8px;`
     
  ---
  6. Check-circle icon sizing on tables should be

     `height: 16px;`
     `width: 16px;`
  ---
  7. Asset section header is missing it should have a section header

     BEFORE:
     
     <img width="1499" alt="Screen Shot 2021-05-19 at 10 06 05 PM" src="https://user-images.githubusercontent.com/6618158/118826862-6d468f00-b8ee-11eb-9654-92a684d1abad.png">

     AFTER:
     
     <img width="1037" alt="Screen Shot 2021-05-19 at 10 06 36 PM" src="https://user-images.githubusercontent.com/6618158/118826934-7d5e6e80-b8ee-11eb-97f8-16ed708a8904.png">


**Assets**

Asset Card
> padding
> font sizing
> file container sizing: 44px
> user icon sizing
> share icon asset
> add asset type

Asset Detail
Change asset Type design pattern
buttons should be outside the card
card border and padding settings
file container
Tile font settings, also outside

Edit Asset
Use the same file component
Spacing between input groups

Distribute Asset
Select person to distribute with: > font color #727272
DATE ACKNOWLEDGE > DATE ACKNOWLEDGED
Status icon sizing and asset
table-striped
Table heading > the sort icon is either going down or separated
The name column is disproportionately bigger than the rest (is it pushing the sort icons down?)


