music_library[title] = song_info
    print(f"Song '{title}' added to the library.")

def remove_song(title):
    if title in music_library:
        del music_library[title]
        print(f"Song '{title}' removed from the library.")
    else:
        print(f"Song '{title}' not found in the library.")

def display_library():
    if not music_library:
        print("The library is empty.")
    else:
        print("Music Library:")
        for title, info in music_library.items():
            print(f"Title: {title}")
            print(f"Artist: {info['artist']}")
            print(f"Album: {info['album']}")
            print(f"Year: {info['year']}")
            print("-----------------------")
