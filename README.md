# Zumble Egg

Zumble voice server egg for FiveM.  
Replaces the default FXServer Mumble server.  
Fixes robotic audio under load.  
Moves voice processing off the main server.

---

## What you get

- External Mumble voice server tuned for FiveM
- Stable voice at high player counts
- Reduced FXServer network load
- Support for rapid channel creation and removal
- Built for proximity voice movement

---

## Why use this

FXServer uses a TCP based Mumble server.  
This setup struggles under load.

You see:
- Robotic or broken voice
- Increased network thread usage
- Voice dropouts during high activity

This setup fixes those issues by moving voice to a dedicated process.

---

## Performance impact

- Frees FXServer network resources
- Handles high channel churn
- Maintains consistent voice quality during peak activity

---

## Resources

- Docs: https://docs.qbox.re/dashboard/zumble  
- Fork and maintained version: https://github.com/AvarianKnight/rust-mumble  
- Original project: https://github.com/SOZ-Faut-etre-Sub/ZUMBLE  

---

## Credits

Zumble:
- Original author: SOZ-Faut-etre-Sub
- Maintainer: AvarianKnight

Egg:
- SantosMods.dev
- BrickHosting.org

---

## License

Zumble is licensed under the MIT License.

Copyright:
- Joel Wurtz, 2022
- SantosMods.dev, 2026

Full license text included in this repository.
