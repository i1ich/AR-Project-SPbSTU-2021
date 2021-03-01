# AR-Project-SPbSTU-2021
## HEAD
### Team members: 
   #### Ilia Doinikov — **techlead**
   #### Alexander Kolodinsky
   #### Yampil Darizhapov — **teamlead**
   #### Ivan Troshchenkov
## BODY
AR Project - interactive quest on SPBSTU campus territory. Quest will include mini-games that based on unique AR mechanics which are often not used in popular AR games.

## Commit requirements:
1.  Language: English
2.  Bare infinitive (add, fix, load)
4.  Header line must begin with issue number(#101)
5.  Brief changes description — in header
6.  What changes have been made — in description
7.  Enumeration in description starts from "-" with space after that. One line — one change.
### Commit example:
#### Header
``` c#
#322 Added textures
```
#### Description
```c++
- added wall texture
- added ground texture
```
## Code style:
  ### Camel case:
       int camelCase;
       class CamelCase...
  ### Comments: 
    Letterhead of file: 
     /*
      * FILE: "###.###"
      * File description(vector declaratioт file e.g.)
      * Members: Vasya Pupkin, Sasha Trubkin
      * Date: 12.12.2012
      */
   #### Classes:
       /*Vector handle class*/
   #### Functions: 
    /* Sum of two vector function
     * ARGUMENTS:
     * - vectors to Add
     *     Vec a, Vec b
     * RETURNS: (Vec) sum of 2 vectors
     */
      Vec Sum(Vec a, Vec b);
   #### Objects in classes:
      // Components
      double x, y, z
   #### Comments are also welcomed before each semantic block of the program:
      // Sort components
      for...
      ...
      

  
 
