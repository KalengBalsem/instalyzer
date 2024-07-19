## Overview
![instalyzer](https://private-user-images.githubusercontent.com/144529349/350314729-c2f831e0-df9c-4fce-bff4-b135b6340d74.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjEzNzY2NTgsIm5iZiI6MTcyMTM3NjM1OCwicGF0aCI6Ii8xNDQ1MjkzNDkvMzUwMzE0NzI5LWMyZjgzMWUwLWRmOWMtNGZjZS1iZmY0LWIxMzViNjM0MGQ3NC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNzE5JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDcxOVQwODA1NThaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1kOTAxMDExZjgxZDZjNGM2Y2U0YjFiMzkzMjk3Yjc4YzA0ZmNiNzE3MTNmNjgzZThiOWNmYTZmMzAyMDcwMmI3JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.qOGTy7SPM7CzTBLC5x9kZEKIJ0Z0Y9xrsLnqc2njQW8)
This project aims to allow us to analyze any IG account with a username using a simple yet powerful instagram data analytic tool.

## Installation and Running
Note: only compatible on Windows
1. open an IDE (recommend: VScode)
2. run the following in the terminal inside the IDE:
```
git clone https://github.com/KalengBalsem/instalyzer.git
```
3. **IMPORTANT** locate the instalyzer file in the terminal:
   ```
   # windows cmd command
   cd instalyzer

   # the end path of the terminal should be instalyzer: PS C:\Users\balse\Documents\VScode\a_folder\instalyzer> 
   ```
6. install the dependencies by running this command in the terminal:
```
pip install -r requirements.txt
```
7. run this command in the terminal to run the server in localhost:
```
# windows
python main.py
PS C:\Users\balse\Documents\VScode\instalyzer> python main.py
####

# output:
Created Database!
 * Serving Flask app 'application'
 * Debug mode: on
WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
 * Running on http://127.0.0.1:5000
Press CTRL+C to quit
 * Restarting with stat
Created Database!
 * Debugger is active!
 * Debugger PIN: 102-884-233
```
8. open the localhost link -> 127.0.0.1:5000
9. done

## Feature
Enter an Instagram (IG) username to generate the following output:
- Main user profile information (user_id, username, full_name, posts_count, followers, following, bio, category)
- IG posts data (likes, comments, hashtags, tagged user, timestamp (upload time), etc.)

Data visualizations:
- Most popular upload day
- Most popular upload time
- Line plot of recent posts' performance (based on likes/comments)
- Note: the user can click on the data, then be given a link directing to that post.
- Top hashtags
- Top caption words
- List of links to Most Liked Posts and Most Commented Posts
