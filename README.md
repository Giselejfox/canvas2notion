# canvas2notion

## Overview
This repository contains a jupyter notebook you can run to upload all your [Canvas](https://www.instructure.com/canvas) assignments from a class into a [Notion](https://www.notion.so/product) database using both canvas and Notion's RESTful api documentation.

[Canvas LMS API Documentation)(https://canvas.instructure.com/doc/api/)
[Notion API Documentation](https://developers.notion.com/)

## Step 1
Create a file in the same directory called secretStuff.py. This is where you'll add in your personal information like your Notion token, your Canvas notion, and your Notion database ID.

## Step 2
Create the following variables in secretStuff.py and fill them by following the instructions for each.

`notion_token` 
In order to interact with the Notion API we have to request a token from them, like a password.

### Step 2.1
Go to [https://developers.notion.com/](https://developers.notion.com/)

### Step 2.2
Click on the 'view my integrations' button in the top right corner

### Step 2.3
Press the '+ New Integration' button

### Step 2.4
Go through the steps on the form. 
Make sure the associated workspace is aligned with where you want the Canvas assignments to end up, other than that the rest of the options don't matter for your own use.

### Step 2.5
Copy down the 'Internal Integration Token' and add it as a variable called `notion_token` to secretStuff.py


<!-- ![front page of notion's developer's site](./README_img/notion_site.png "Test") -->

IN CONSTRUCTION
