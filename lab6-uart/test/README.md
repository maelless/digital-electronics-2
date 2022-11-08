# Lab 6: MAELLE SORIANO

### ASCII

1. Complete the table with selected ASCII codes.

   | **Char** | **Decimal** | **Hexadecimal** | **Binary** |
   | :-: | :-: | :-: | :-: |
   | `a` | 97 | 0x61 | `0b0110_0001` |
   | `b` | 98 | 0x62 | `ObO110_0010` |
   | `c` | 99 | 0x63 |  `0b0110_0011`|
   | `0` | 48 | 0x30 | `0b0011_0000` |
   | `1` | 49 | 0x31 | `0b0011_0001` |
   | `2` | 50 | 0x32 | `Ob0011_0010` |
   | `Esc` | 27 | 0x1B |`Ob0001_1011`  |
   | `Space` | 32 | Ox20 | `Ob0010_0000` |
   | `Tab` | 9 | 0x09 | `0b0000_1001` |
   | `Backspace` | 8 | 0x08 |`0B0000_1000`  |
   | `Enter` | 13-10 |Ox Od Oa  | `Ob 0000_1101` `OOOO_1010` |

### UART communication

2. Draw timing diagram of the output from UART/USART when transmitting three character data `De2` in 4800 7O2 mode (7 data bits, odd parity, 2 stop bits, 4800&nbsp;Bd). The image can be drawn on a computer or by hand. Name all parts timing diagram.

   ![image](https://user-images.githubusercontent.com/114487158/200688193-d2a5821d-793a-448a-b9ad-dc0c5ba1de11.png)


3. Draw a flowchart for function `uint8_t get_parity(uint8_t data, uint8_t type)` which calculates a parity bit of input 8-bit `data` according to parameter `type`. The image can be drawn on a computer or by hand. Use clear descriptions of individual algorithm steps.

   ![image](https://user-images.githubusercontent.com/114487158/200688285-c6654654-98a8-4255-ba42-8f7e20f28ea0.png)

