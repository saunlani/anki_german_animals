# 🐾 anki_german_animals

A picture-based Anki deck that helps you master German animal nouns across **all four grammatical cases** (nominative, accusative, dative, genitive), in both **singular and plural**.

I first put this deck together for my own learning, but it’s perfect for anyone who wants more than just vocab drills — it’s about seeing how German nouns actually work in real, full-sentence context with the bonus of identifying animals in German.

---

## 🧠 What’s in the Deck

Each animal appears in 8 forms:

- Nominative Singular
- Accusative Singular
- Dative Singular
- Genitive Singular
- Nominative Plural
- Accusative Plural
- Dative Plural
- Genitive Plural

Each card includes:
- A photo of the animal  
- A sentence with blanks (for article + noun)  
- A completed version of the sentence  
- The English name of the animal  

---

### 📋 Example Card

#### Front  
<img src="bear.jpg" alt="Bear" width="200" />

#### Accusative Singular
Ich sehe <ins>_________</ins>  im Wald.

#### Back
<img src="bear.jpg" alt="Bear" width="200" />

#### Accusative Singular
Ich sehe <ins>den Bären</ins> im Wald.

“Bear”

---

## 🛠️ How It Was Built

The deck is generated using a Python script that:
- Loads a CSV file containing nouns and example sentences in each case  
- Replaces the article + noun with underlined blanks  
- Formats the front/back of each card using a custom `genanki` template  
- Includes a photo for each animal (stored in `/images`)  
- Exports everything into a `.apkg` file with media bundled

---

## 🎯 Why Use This Deck?

- Internalize article + noun patterns through **visual and contextual repetition**
- Tackle tricky topics like **N-Deklination** with consistent exposure
- Focus on **sentence-level acquisition** rather than isolated vocab
- Works great for A1–C2 learners who are tired of drilling declension charts or vocab lists in a vacuum

---

## 📦 Using the Deck

To use the deck:
1. Download the `anki_german_animals.apkg` file (see [Releases](https://github.com/saunlani/anki_german_animals/releases/latest))  
2. Import it into Anki  
3. Start reviewing!

You’ll need [Anki](https://apps.ankiweb.net) installed on your device.

---

## 🐛 Feedback or Fixes?

Feel free to open an issue or submit a pull request :).
