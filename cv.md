## [rsschool-cv](https://SidoryakaSergey.github.io/rsschool-cv/cv)

---

# Sergey Sidoryaka

---

### Contact

---

- **Location:** Kiev, Ukraine
- **Phone:** +380 50 471 9094
- **email:** s.sidoryaka@gmail.com
- **GitHub:** sidoryakasergey

## **About Me**

---

Professional installation and configuration of the entire family of Windows, and FreeBSD and Ubuntu. Installation and ability to work with packages Adobe, Sony and others. Software. Build and configure servers and workstations, as well as troubleshooting. Writing small programs and scripts to automate.

## **Skills**

---

- HTML/CSS
- JavaScript
- Visual Basic / C# (Basic)
- Git
- Photoshop
- Administration

## **Code Example**

---

```function codility() {
  const len = A.length;
  if (len === 0) {
    return 1;
  }
  if (len === 1) {
    if (A[0] === 1) {
      return 2;
    } else {
      return A[0] - 1;
    }
  }
  A.sort((a, b) => {
    return a - b;
  });
  for (let i = 0; i < len - 1; i++) {
    if (A[i] + 1 != A[i + 1]) {
      return A[i] + 1;
    }
  }
  if (A[0] === 1) {
    return A[len - 1] + 1;
  } else {
    return A[0] - 1;
  }
}
```
