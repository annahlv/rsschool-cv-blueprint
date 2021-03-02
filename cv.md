# Anna Holovan
Kyiv, Ukraine

annahlv.work@gmail.com

+380 67 382-15-18

###### Experience
#### Web Designer
ООО «Дэксэтсервис» (OOO Dexatservice)

Nov 2018 - Oct 2020 - 2 years, Minsk, Belarus

UI design, graphic design, corporate print design. Our main project
was creating the website for car rental service using the .NET Core
platform. During that time I earned some valuable experience in
design and web development.

###### Education
#### Belarusian State Technological University
2016 - 2020, Minsk, Belarus

Bachelor’s degree in Design of Electronic and Web Publications.
Here I've taken courses in interface design, math, cryptography, frontend/backend programming, image/video processing, animation, 3D modelling, project management, etc.

###### Code examples
      var collection = {
        2548: {
        albumTitle: 'Slippery When Wet',
        artist: 'Bon Jovi',
        tracks: ['Let It Rock', 'You Give Love a Bad Name']
        },
        2468: {
        albumTitle: '1999',
        artist: 'Prince',
        tracks: ['1999', 'Little Red Corvette']
        },
        1245: {
        artist: 'Robert Palmer',
        tracks: []
        },
        5439: {
        albumTitle: 'ABBA Gold'
        }
    };
  
    function updateRecords(object, id, prop, value) {
        if (prop !== 'tracks' && value !== "") {
        object[id][prop] = value;
        } else if (prop === "tracks" && !object[id].hasOwnProperty("tracks")) {
        object[id][prop] = [value];
        } else if (prop === "tracks" && value !== "") {
        object[id][prop].push(value);
        } else if (value === "") {
        delete object[id][prop];
        }
        return object;
    }
  
    updateRecords(collection, 5439, 'artist', 'ABBA'); 
###### Technologies
HTML, CSS, JavaScript, Node.js, C#, .NET, PHP, SQL, LINQ, Unity, Git

###### English level
B2
