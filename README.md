# komariherring.github.io

If we want to add contents to a preexisting string, we use the method insert(contentsOf:at: and insert(_:at:). 
These methods let us add a single character or another string into a preexisting one. 


“var komari = "TheIron"
“komari.insert(contentsOf:"Yard".characters, at: komari.index(before: komari.endIndex))”
// komari now equals TheIronYard

 
komari.insert("!", at: komari.endIndex)
// komari now equals "TheIronYard!”

