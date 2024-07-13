const welcomeMessage = "\u0627\u0644\u0643\u0648\u062f\u0020\u0627\u0647\u062f\u0627\u0621\u0020\u0627\u0644\u0649\u0020\u0627\u0644\u0639\u0645\u0020\u0627\u0646\u062a\u0642\u0627\u0645\u0028\u0020\u006a\u0069\u0068\u0061\u0064\u0020\u0029\u002e\u0020\u0627\u0636\u063a\u0637\u0020\u0645\u0648\u0627\u0641\u0642\u0020\u0644\u0644\u0628\u062f\u0621\u002e";
const confirmation = confirm(welcomeMessage);

if (confirmation) {
    const newWord = prompt("\u0627\u062f\u062e\u0644\u0020\u0627\u0644\u0643\u0644\u0645\u0647\u0020\u0627\u0644\u0645\u0637\u0644\u0648\u0628\u0647\u003a");
    if (newWord) {
        const fillSpeed = prompt("\u0633\u0631\u0639\u0629\u0020\u0643\u062a\u0627\u0628\u0629\u0028\u0031\u0030\u0030\u0029\u003a");
        const saveSpeed = prompt("\u0633\u0631\u0639\u0629\u0020\u0627\u0644\u062d\u0641\u0638\u0020\u0028\u0032\u0035\u0030\u0030\u0029\u003a");

        const inputFields = document.getElementsByClassName("\x69\x6e\x70\x75\x74\x20\x66\x75\x6c\x6c\x20\x70\x72\x6f\x66\x69\x6c\x65");
        if (inputFields.length > 1) {
            inputFields[1].value = newWord;
        }
        setTimeout(function kh_fill() {
            const inputFields = document.getElementsByClassName("\x69\x6e\x70\x75\x74\x20\x66\x75\x6c\x6c\x20\x70\x72\x6f\x66\x69\x6c\x65");
            if (inputFields.length > 1) {
                inputFields[1].value = newWord;
            }
            setTimeout(kh_fill, fillSpeed);
        }, 1);

        setTimeout(function kh_click() {
            const button = document.querySelector('\x64\x69\x76\x5b\x64\x61\x74\x61\x2d\x6f\x6e\x63\x6c\x69\x63\x6b\x3d\x22\x42\x4c\x41\x5a\x45\x2e\x67\x6c\x6f\x62\x61\x6c\x2e\x70\x66\x5f\x73\x61\x76\x65\x22\x5d');
            if (button) {
                button.click();
                BLAZE.global.pf_save();
            }
            setTimeout(kh_click, saveSpeed);
        }, 3000);

        console.clear();
    } else {
        alert("\u0644\u0645\u0020\u064a\u062a\u0645\u0020\u062a\u0646\u0641\u064a\u0630\u0020\u0627\u0644\u0643\u0648\u062f\u002e");
    }
} else {
    alert("\u0644\u0645\u0020\u064a\u062a\u0645\u0020\u062a\u0646\u0641\u064a\u0630\u0020\u0627\u0644\u0643\u0648\u062f\u002e");
}
