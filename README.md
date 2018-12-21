# Nutrient Sync

Nutrient Sync is an iOS Shortcut I made to get around the privacy concerns and subscription based focus of most calorie tracking apps. This utilizes your iCloud Drive to store data and iOS Health to sync the data.

## Current Version

Version 0.1.1

## Install

In order to utilize Nutrient Sync, you must add these to Shortcuts to your library:

- [Nutrient Sync](https://www.icloud.com/shortcuts/e2f753701227484da5fe288a529dbaa8) (To run Nutrient Sync)
- [libNutrientSync](https://www.icloud.com/shortcuts/f57f4d28fb7544989bd443a041bdc943) (A library of functions that Nutrient Sync is dependent on.)

On the first run, it will create a file in _/iCloud Drive/Shortcuts/_ called **nutrientsync-setup.txt** and a folder called **Nutrient Sync**. Inside of the **Nutrient Sync** folder are two folders named **Food** and **Drink**.

Any saved items you create with Nutrient Sync will be saved in **Food** or **Drink** when you specify what type it is. When you use the _Load Saved Item_ option, you will need to navigate to those folders when it prompts you.

## Run Options

### Enter Item to Health

- Enter the time the item was consumed at.
- Select the nutrients you want to record.
- Enter the data for each prompt.
- Returns that data to the Health app.
- Asks if you want to save the item.

### Enter Item to iCloud

- Select the nutrients you want to record.
- Enter the data for each prompt.
- Prompts to save item.

### Load Saved Item

- Prompts to load a file.
- Asks which nutrients to sync.
- Asks the time the item was consumed.
- Returns the data to the Health App.

### Check for Update

- Checks this GitHub repo for any updates that I may have done.