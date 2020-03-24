# gift-card-marketplace
Some Liquid and CSS to help Shopify users setup a "Gift Card Marketplace" with a better user experience. 

### **This is a temporary solution to a complex problem.**

## Why do I need this?
By default, when you click "View Gift Card" after you purchase a gift card from a Shopify store, the image used is NOT the Primary photo used on the Gift Card product itself. 

These changes offer two major distinctions:
1. The image used after purchase will be the primary image from the Gift Card Product (please use the template attached here for best sizing)
2. It add the customers Name and Email address to the gift card for better verification capabilities.

## I don't want to touch code!
If you have an unmodified version of one of the Shopify Themes, you can download a complete theme package [from this link](https://drive.google.com/drive/folders/1ZBMLuq9tRc19WMzrKltEHqzmFF7ze4SA?usp=sharing).

**You will still be required to Customize the theme using the Theme Editor!** While this will eliminate the need to get into the code, it's basically a fresh install with customizations already done for you.

## What am I getting here?
This repository contains a couple things you will need.
1. **templates/gift_card.liquid** - This file contains all the changes to the gift card page
2. **gift-card-css.md** - This file contains multiple blocks of CSS, these will go at the bottom of your *theme.scss.liquid* file. *You will only need the CSS specific to the theme you are using, make sure to copy the correct one*!
3. **Image** - The default Gift Card image for you use as a base to create your own.

## Instructions
Step by step instructions to make these changes. You can [watch a video here](https://drive.google.com/a/shopify.com/file/d/1ZdvbCY_i-0IQfbtSPR-VNAaJxFfAx49w/view?usp=sharing). 

It's best if you have your store Admin open in one tab and the files you will need in 

1. In your Shopify Admin, go to **Online Store**
2. Click on **Actions** and choose **Edit Code** | [Screenshot](https://screenshot.click/24-44-otdzf-lah5y.jpg)
3. Open **Templates/gift_card.liquid**, select all the contents and delete. **DO NOT** modify the **Layout/gift_card.liquid**. | [Screenshot](https://screenshot.click/24-50-kj5xx-nyh3d.jpg) 
4. Open/Switch to the **Templates/gift_card.liquid** file provided here. Select all the contents and **Copy**.
5. In your Shopify Admin, **Paste** your clipboard into the empty **templates/gift_card.liquid** and click **Save** | [Screenshot](https://screenshot.click/24-53-wyb70-wxmft.jpg)
6. DEBUT USERS, YOU'RE DONE! Other themes, continue to next step.
7. Open the **gift-card-css.md** file provided here and find the block of CSS for your theme. Select it and **Copy** | [Screenshot](https://screenshot.click/24-56-r0dg3-zqpxe.jpg)
8. In your Shopify Admin, navigate to **Assets/theme.scss.liquid** and scroll to the very bottom of the file (these can be VERY long). Place your cursor at the end of the very last line and hit return a few times and then **Paste** the CSS block you copied and click **Save** | [Screenshot](https://screenshot.click/24-58-0jzyq-t20qb.jpg)
9. That's it! All the code is updated :D
