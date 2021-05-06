Install:

    curl https://raw.githubusercontent.com/OverdueWeevil2/Xfce-packages/main/setup-with-autoyes.sh | sudo bash
Remove:

    curl https://raw.githubusercontent.com/OverdueWeevil2/Xfce-packages/main/remove-with-autoyes.sh | sudo bash && sudo apt autoremove -y
Reinstall:

    curl https://raw.githubusercontent.com/OverdueWeevil2/Xfce-packages/main/remove-with-autoyes.sh | sudo bash && sudo apt autoremove -y && curl https://raw.githubusercontent.com/OverdueWeevil2/Xfce-packages/main/setup-with-autoyes.sh | sudo bash
