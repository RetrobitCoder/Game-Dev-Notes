# Arduboy
----
## Important Links
- [Arduboy Website](https://arduboy.com/)
- [Arduboy Community Page](https://community.arduboy.com/)
- [Arduboy2 Library Documentation](https://mlxxxp.github.io/documents/Arduino/libraries/Arduboy2/Doxygen/html/index.html)

## Notes
Notes are ranked in the order that I think is most important to remember with 1 being the most important

1. It seems to be best not to create a bunch of objects, but instead re-use objects to save memory. Example: created enemy object for level 1, 
on level 2 re-use same object and just update what needs to be updated for level 2.
2. Most of the methods in the Arduboy2 library are static and don't need to create an instace of Arduboy to use them.
3. May be something specific to Arduino or the Arduino board Arduboy uses, but not able to throw errors. Would be better to return non-possible value to signify error like in C.
