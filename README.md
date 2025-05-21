<h1>Hi, I'm Smriti Sahu! <a>Cybersecurity Professional</a></h1>

<h2>👩‍💻 Cybersecurity Projects:</h2>

<ul>
  <li><b>Network Spyglass: Wireshark & tcpdump in Action</b>
    <ul>
      <li><a href="https://coursera.org/share/011a7887a4e3eda11059443a13d33ba6" target="_blank">Wireshark: Capture Packets</a></li>
    </ul>
  </li>

 - **Implementing Caesar Cipher**
  - A Python tool that allows users to input a message and shift value to perform encryption and decryption using the classic Caesar Cipher algorithm.
  - ```python
    def caesar_cipher(text, shift):
        result = ""
        for char in text:
            if char.isalpha():
                shift_base = ord('A') if char.isupper() else ord('a')
                shifted = (ord(char) - shift_base + shift) % 26 + shift_base
                result += chr(shifted)
            else:
                result += char
        return result

    # Example usage
    message = "Hello, World!"
    shift_value = 3
    encrypted = caesar_cipher(message, shift_value)
    print("Encrypted:", encrypted)
    ```
  - [View Code on GitHub](https://github.com/smritisahuu/cybersecurity-projects/blob/main/Caesar-Cipher/caesar_cipher.py)

  
  <li><b>Image Encryption via Pixel Manipulation</b>
    <ul>
      <li>A Python program that encrypts and decrypts images by shuffling pixel data using a secret key.</li>
      <li><a href="https://github.com/YOUR-USERNAME/cybersecurity-projects/blob/main/Image-Encryption/encrypt_decrypt_image.py" target="_blank">View Code on GitHub</a></li>
    </ul>
  </li>

  <li><b>Password Complexity Checker</b>
    <ul>
      <li>A Python script to assess the strength of passwords based on length, use of uppercase, lowercase, digits, and symbols.</li>
      <li><a href="https://github.com/YOUR-USERNAME/cybersecurity-projects/blob/main/Password-Checker/password_checker.py" target="_blank">View Code on GitHub</a></li>
    </ul>
  </li>

  <li><b>Keylogger Program (Educational Purpose Only)</b>
    <ul>
      <li>A Python keylogger that records and logs keystrokes for research and ethical learning purposes.</li>
      <li><a href="https://github.com/YOUR-USERNAME/cybersecurity-projects/blob/main/Keylogger/keylogger.py" target="_blank">View Code on GitHub</a></li>
    </ul>
  </li>
</ul>

<h2>📃 Certifications</h2>

<ul>
  <li><a href="https://coursera.org/share/cba3e014a9d3571f4a6dba90945c5a8c" target="_blank">Google Cybersecurity Professional Certificate</a></li>
  <li><a href="https://tryhackme-certificates.s3-eu-west-1.amazonaws.com/THM-IPPIEG9CSS.pdf" target="_blank">TryHackMe Security Engineer Certificate</a></li>
  <li><a href="https://coursera.org/share/6d0a7d4d6cc5194c639a9f85b58de634" target="_blank">InfoSec OWASP Top 10 - 2021</a></li>
  <li>Qualys Vulnerability Management Foundation</li>
</ul>



