# Mandarin Learning Chatbot 🀄

An AI-powered chatbot designed to help users learn **Mandarin Chinese through conversation**.  
The bot simulates real text-message style dialogue so learners can practice vocabulary, pronunciation hints, and sentence structure naturally.

This project focuses on **interactive learning instead of memorization**.

---

## Features

- 💬 Conversational Mandarin learning
- 🧠 Vocabulary + grammar reinforcement
- 📖 Structured dialogues from training scripts
- ⚡ Lightweight and easy to run
- 🤖 Designed to integrate with AI models

---

## Example Conversation

Below is an example Conversation with the chatbot.

```
User : Hello there!
ChatBot : 你好 (Nǐ hǎo) [Hello]! I'm 李老师 (Lǐ lǎoshī), your Mandarin teacher. I'll guide you through learning Mandarin step by step. May I know your name to give you a Chinese name?

Understanding your name helps personalize your learning experience.

User : I'm Rohan. It's very nice to meet you!
ChatBot : 很高兴认识你 (Hěn gāoxìng rènshí nǐ) [It's very nice to meet you too], Rohan! Your Chinese name could be 罗汉 (Luó Hàn). Would you like to keep this name or change it?

Choosing a name you like can make learning more enjoyable.

User : It seems good. Does it have a special meaning associated with it?
ChatBot : 罗汉 (Luó Hàn) is a good name. It can mean "Arhat," a respected figure in Buddhism, symbolizing virtue and protection. Are you happy with this name?

Your connection with your name can enhance your learning motivation.
```

The chatbot dialogue is stored in: [Dialogue_2024-04-13_00-07-56.txt](Dialogue_2024-04-13_00-07-56.txt) (See dialogue.txt for full conversation)

The chatbot reads this file and delivers responses sequentially to simulate a conversation.

---

## Project Structure

```
Li_Lao_Shi
│
├── LangChainBot.ipynb
├── Dialogue_2024-04-13_00-07-56.txt
├── requirements.txt
└── README.md
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/rohankar7/li_lao_shi.git
cd li_lao_shi
```

---

## Future Improvements

- Voice pronunciation practice
- Tone detection
- AI-generated dialogues
- Difficulty levels (HSK 1 → HSK 6)
- Web app interface

---

## License

MIT License