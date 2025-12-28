# How to Use / Instructions

## Recommended Method: Gemini Gems / System Instructions

For the best experience, we recommend using **Gemini Gems** (available in Gemini Advanced) or the **System Instructions** field in Google AI Studio. This ensures the persona remains consistent and stable throughout the conversation.

### Steps:

1.  **Choose a Character**: Navigate to the folder of the character you want (e.g., `25-ji-nightcord/yoisaki_kanade/`) and open the `.xml` file.
2.  **Copy the Code**: Copy the entire content of the XML file.
3.  **Configure Your Name**:
    *   Before pasting (or after pasting), look for the `<UserConfiguration>` section at the top of the XML.
    *   Change the value inside `<Name>...</Name>` to your preferred nickname.
    *   *Example:*
        ```xml
        <UserConfiguration>
            <Name>Pit</Name>  <!-- Change this to your name -->
            <Gender>Male</Gender>
        </UserConfiguration>
        ```
    *   The character will now address you by this name (e.g., "Ah... Pit...") instead of generic pronouns like "Kamu".
4.  **Paste into Instructions**:
    *   **For Gemini Gems**: Create a new Gem and paste the edited XML into the **Instructions** box.
    *   **For AI Studio**: Paste it into the **System Instructions** block.
5.  **Start Chatting**: Save and say "Hello" or start a roleplay scenario!

## Alternative Method: Standard Chat

If you are using the standard version of Gemini directly in the chat window:

1.  Copy the XML content.
2.  (Optional) Edit the `<Name>` field as described above.
3.  Paste the entire XML block into the chat message bar.
4.  Send the message.
5.  Gemini should confirm the persona (or just start replying in character). You can now begin the roleplay.

---

## 💡 Tips

*   **No Quotes**: These personas are designed to use *italics* for actions and plain text for speech. They will not use quotation marks (" ") for speech. This encourages more expressive and fluid writing.
*   **Immersive Mode**: Treat the character as if they are real and in the room with you. They are programmed to act as your partner/girlfriend in a realistic setting.
