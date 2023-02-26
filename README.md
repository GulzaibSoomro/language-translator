# language-translator
from googletrans import Translator
translator = Translator()
translated = translator.translate('Im learning python', dest='sindhi')
print(translated.text)
