# 🔮 JavaScript Checkpoint Project — Zodiac Sign Finder

This project is a simple **JavaScript script** that determines and prints the **zodiac sign** based on the value of a given **month**.

It serves as a basic checkpoint project to practice conditional logic using `if-else` statements in JavaScript.

---

## 📌 How It Works

- A variable called `months` is initialized with a month name (e.g. `"January"`).
- The script checks the value of `months` using a series of `if-else` statements.
- Based on the value, it logs the corresponding zodiac sign to the console.

---

## ♈ Zodiac Sign Output Logic

Here’s how the script maps months to zodiac signs:

| Month      | Output                         |
|------------|--------------------------------|
| January    | You are a Capricorn ♑          |
| February   | You are an Aquarius ♒          |
| March      | You are a Pisces ♓             |
| April      | You are an Aries ♈             |
| May        | You are a Taurus ♉             |
| June       | You are a Gemini ♊             |
| July       | You are a Cancer ♋             |
| August     | You are a Leo ♌                |
| September  | You are a Virgo ♍              |
| October    | You are a Libra ♎              |
| November   | You are a Scorpio ♏            |
| December   | You are a Sagittarius ♐        |

If the value of `months` does **not** match any valid month, it logs:

```text
Invalid month entered
