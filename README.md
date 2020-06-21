Fork from [davidchua/pymessenger](https://github.com/davidchua/pymessenger)
=========================

**Follow function is added:**

- send_quick_reply_message(recipient_id, text, quick_replies)

**Follow function is fixed:**

- send_message(recipient_id, message): Now you can pass just the raw message instead of the json block { 'text' : 'raw_message' }
