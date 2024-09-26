# Korean SVG Font

This project is to revive the original Korean character(Hun-min-jeong-um)
When the great king Seajong made Korean characters, it contained 28 characters and a flexible rule to make all sounds in the world. But when Korean pass through Japansese ruling era(1910.8.29 ~ 1945.8.15), Korean character is "standardized" removing 4 basic characters and nature of flexibility.
In this project, I want to make the old Korean writing method with gamific application, and link all the possible Korean typing system, and fonts.

## Boundary
This project includes:
- Old Korean writing game (Web Application)
- Korean SVG Font Generator (Web Application)
- Korean Hunminjeongum Keyboard (React Native App)
- Korean SVG Font (javascript library)

## Milestone
this project is a long term project. the milestone is like below:

### research 
  - all the existing old korean writing systems
  - all the existing old korean fonts
  - how to make mobile font keyboard
  - how to make mac/windows keyboard

## Architecture
### SVG Korean Font
  - svg representation of text
  - flexible character generation algorithm(option can be used for gap, size..)
### Old Korean writing game / Korean SVG Font Generator
  - make each characters as 1 independent svg
  - put svg in a line. space will be just empty svg which holds just space
  - consider special characters (don't know? then just x4(or option) and add svg
  
