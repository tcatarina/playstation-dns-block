# playstation-dns-block

Collection of DNS hosts, with the purpose of blocking playstation servers to prevent system updates.

You should be able to add this list to your MikroTik Adlist, or even as a source in your PI-Hole.

---

### MikroTik

1.  In your RouterOS configuration, navigate to **IP** > **DNS**.
2.  Go to the **"Adlist"** tab and click the **"+"** (New) button.
3.  Paste the [raw host file URL](https://raw.githubusercontent.com/tcatarina/playstation-dns-block/refs/heads/main/hosts) into the **"URL"** field.
4.  You may need to uncheck the **SSL Verify** checkbox.
5.  Click **"OK"**. The list will be fetched automatically.

---

## Credits

This host list was originally collected by **[Al-Azif](https://gist.github.com/Al-Azif/296c7a4319c2fe3b597d96206213cdb6)**. All credit for the entire collection and research goes to him. This repository simply maintains it in a format easily consumable by MikroTik RouterOS.

## License

This project is licensed under the [MIT License](LICENSE).
