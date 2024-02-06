import customtkinter as ctk
from deep_translator import GoogleTranslator

def translate_language():
    text_to_trans = user_text.get()
    lang = lang_to_var.get()

    output = GoogleTranslator(source="auto", target=lang).translate(text_to_trans)

    translated_text.configure(state="normal")
    translated_text.delete(0, "end")
    translated_text.insert(0, output)

root = ctk.CTk()
root.title("Language translator")
root.minsize(400, 400)

ctk.set_appearance_mode('dark')
ctk.set_default_color_theme('dark-blue')
