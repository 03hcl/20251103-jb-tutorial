---

---

# New File 2

[My favorite equation](eq_newton)

(my-label)=
Add a label to this paragraph.

[](my-label)

[](xref:ttw)
[](xref:ttw#ch-infrastructure-dns)

[](tl_basic_formatting)

:::{code-cell} python
def fib(n):
    if n < 0:
        return
    if n in (0, 1):
        return n
    return fib(n - 2) + fib(n - 1)

for i in range(10):
    print(i, fib(i))
:::
