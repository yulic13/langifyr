import streamlit as st

def translate_to_english(text):
    # Placeholder translation logic
    # In reality, you'd call the OpenAI API or another translation service here
    translated_text = text[::-1]  # This just reverses the string as an example
    return translated_text

# Layout of the web app
st.title('Text Translator to English')

# Split the page into 2 columns
col1, col2 = st.columns(2)

# Text input in the left column
with col1:
    st.header('Enter your text:')
    input_text = st.text_area('')

# Translation display in the right column
with col2:
    st.header('Translation to English:')
    if input_text:
        translated_text = translate_to_english(input_text)
        st.write(translated_text)

