# Sisteme de Operare – Capitolul 5

**1.** Realizați o bibliotecă de funcții matematice care să cuprindă funcții de adunare și înmulțire a două matrici.

**2.** Realizați un program care folosește biblioteca de mai sus.

**3.** Pentru întreținerea bibliotecii, precum și pentru compilarea programului de la 2, realizați un fișier make cu opțiunile:
- `prg` – creează executabilul de la 2;
- `bibl` – creează biblioteca de la 1;
- `clean` – șterge fișierele temporare.

## Fișiere

| Fișier | Problema |
| --- | --- |
| `matrice.h` | 1 – declarațiile funcțiilor din bibliotecă |
| `matrice.c` | 1 – corpul funcțiilor din bibliotecă |
| `program.c` | 2 – programul care folosește biblioteca |
| `makefile` | 3 – opțiunile `prg`, `bibl`, `clean` |

Rulare: `make prg`, apoi `./prg`.
