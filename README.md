# BondolAI (Local + Server Edition)
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Python Version](https://img.shields.io/badge/Python-3.9+-brightgreen.svg)](https://www.python.org/)
[![made with love by Henri](https://img.shields.io/badge/made%20with%20love%20by-Henri-ff69b4.svg)](https://github.com/Henriazz10)

Welcome, how are you? In this repository contains a full app that support "State-Of-Art" models
of Google, Mistral and Open Access (With Ollama)


**Important: This version supports local and server models. 
If you only need server-side models (which requires lower local resources), please check out the server-only edition at: 
Henriazz10/BondolAI-Server**

## **¿How to use this code?**

To use this code, the only things that you need to do are;
- First, you clone  all the code in a folder on your PC
  ```bash
  git clone      https://github.com/Henriazz10/BondolAI-Local-and-Server.git
  cd BondolAI-Local-and-Server
  ```
- Then, you need to install all libraries of requeriments.txt
  ```bash
  python -m venv .venv
  .\.venv\Scripts\activate
  ```
  ```bash
  pip install -r requirements.txt
  ```
- After that you have to download this Open-Access models of Ollama (I am working to automatize this step):

  (If you dont have ollama instaled, you can do it from here: [ollama.com](https://ollama.com/download)
```  
    'gemma3:1b', 'gemma3:4b', 'gemma3:12b', 'gemma3:27b',
    'gemma3:1b-it-qat','gemma3:4b-it-qat','gemma3:12b-it-qat',
    'llama3.2', 'llama3.2:1b', 'llama2-uncensored', 'codellama',
    'deepseek-r1:8b',
    'phi4', 'phi4-mini',
    'qwen3:0.6b', 'qwen3:1.7b', 'qwen3:4b', 'qwen3:8b', 'qwen3:30b-a3b'
  ```
- Finally, you must to execute this comand in your .venv (Cmd):

   ```bash
    cd [DOWNLOAD_PATH]
    .venv\scripts\activate
    streamlit run main.py
   ```
  When you already complete this easy 4 steps, you can open the web browser and put "localhost:8501" and
  my app is going to work (I hope)


# How to support me!

This project is a labor of love, developed by a passionate young programmer. If you enjoy using BondolAI and would like to support its development, here are a few ways you can help.

## By crypto
- Bitcoin: `bc1qeysdwwm3vjesyvhnd9fqay23txgqj9kn5vw6dt`
- USDT (Tether ERC20): `0xFA6159360D01B57D18730577035d6B09777c7EF4`
- Ethereum: `0xFA6159360D01B57D18730577035d6B09777c7EF4`

**No pressure at all!!!! I did Bondol for Hobby**; however, your support is welcome

## Reporting:

-   **Found a bug?** Please [open an issue](https://github.com/Henriazz10/BondolAI-Local-and-Server/issues) and describe what went wrong.
-   **Have an idea?** Feel free to open an issue to suggest a new feature.
-   **Want to contribute code?** [Pull Requests](https://github.com/Henriazz10/BondolAI-Local-and-Server/pulls) are always welcome!


# About ME:

Thanks for your support!. I am a child who lives in Argentina; I only have 14 years, and I dream with
work in Google DeepMind someday... And every report of your part, helps me with that objetive!

