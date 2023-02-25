// by m1lean
// by m1lean
function generatePassword() {
    let password = "";
    let length = 18;

    const chars = '1234567890qwertyuioplkjhgfdsa' +
        'zxcvbnmQWERTYUIOPASDFGHJKLZXCVBNM!@#$%^&*';

    const arr = new Uint32Array(length);

    window.crypto.getRandomValues(arr);

    for (let i = 0; i < length; i++) {
        password += chars[arr[i] % chars.length];
    }

    return password;
}
// by m1lean
// by m1lean
