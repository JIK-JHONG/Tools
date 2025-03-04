color_definitions.h 文字顯示色彩標頭檔（Ｃ語言）：
-

基本作用在於在 printf 中，可以實現”顏色標示“，來提升辨別度

color_definitions.h Text display color standard list (C language):
-

The basic role is in printf, which can realize "color standard" to improve the recognition


# include color set file - color_definitions.h
#include "<path>>color_definitions.h"

# Using Method

**<color> + " Your Text " + RESET**

printf("Plot saved as "<color>"'dynamic_plot.png'"RESET"\n");


# COLOR_DEFINITIONS_H 

| Action | Code | ASCII |  
|-------|-------|-------|
| RESET | Color Reset | \033[0m |
| RED | Red | \033[31m| 
| YELLOW | Yellow | \033[33m | 
| GREEN | Green | \033[32m | 
| BLUE | Blue | \033[34m | 