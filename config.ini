# pip install Pyrogram TgCrypto
from pyrogram import Client

api_id = 941514
api_hash = "2b8e24188631929de4bda0c008ba1685"

with Client(":memory:", api_id, api_hash) as app, open("session.txt", "w+") as s_file:
    session_string = app.export_session_string()
    s_file.write(session_string)
    print("Session string has been saved to session.txt")
    print(session_string)
