
Question 1

Problem Statement: Joy recently shifted to California for his new job. He
loves exploring new cafes. Though he managed to get some data related
to nearby cafes, he needs some help to arrange them for easy access.
He got 2 data sets: cafes and places.
cafes is basically an array of cafes (objects). It contains two properties:
name of the cafe and corresponding place's id as place_id
Following is the cafes array
[
{
"name": "Bazaar Cafe",
"place_id": "kjk234g4gcvfx8usg1l33pi"
}, {
"name": "Ashley's Cafe",
"place_id": "12hydbdf76sljfts87sbfis"
}, {
"name": "Avenue Cafe",
"place_id": "skjd86svvfdrsv55svbvf3f"
}, {
"name": "Hi-Lo Cafe",
"place_id": "mjdhgetr4pojfyts22fzfsh"
}, {
"name": "California Chicken Cafe",
"place_id": "12hydbdf76sljfts87sbfis"
}, {
"name": "Avenue Bakery Cafe",
"place_id": "jahgde7wgdiau8ewsahgosd"
}, {
"name": "Philz Coffee",
"place_id": "urhw3837ehalod7w02b7835"
}
]
places is an array containg the details of all the places in California.
Following is the places array
[

{
"id": "jahgde7wgdiau8ewsahgosd",
"street_no": "60H",
"locality": "Solomos Island Road",
"postal_code": "20688",
"lat": "36.7783 N",
"long": "119.4179 W"
}, {
"id": "12hydbdf76sljfts87sbfis",
"street_no": "1B",
"locality": "Macarthur Blvd",
"postal_code": "20619",
"lat": "38.1781 N",
"long": "118.4171 W"
}, {
"id": "kjk234g4gcvfx8usg1l33pi",
"street_no": "45250",
"locality": "Worth Avenue, Unit A",
"postal_code": "20619",
"lat": "36.1152",
"long": "117.521"
}, {
"id": "saswe3s6yydtdr52hsd72yst",
"street_no": "1X",
"locality": "Macarthur Blvd",
"postal_code": "20687",
"lat": "36.7783",
"long": "119.4179"
}, {
"id": "skjd86svvfdrsv55svbvf3f",
"street_no": "7S",
"locality": "Three Notch Road",
"postal_code": "20619",
"lat": "36.83",
"long": "119.6"
}, {
"id": "mjdhgetr4pojfyts22fzfsh",
"street_no": "22803",
"locality": "Gunston Dr Lexington Park",
"postal_code": "20688",
"lat": "35.7788",
"long": "119.979"
}, {
"id": "urhw3837ehalod7w02b7835",

"street_no": "225",
"locality": "Macarthur Blvd",
"postal_code": "20687",
"lat": "35.77813",
"long": "119.41791"
}
]
You have to design a function which will take a string as an argument. It
will search cafes' names containing the searched term as a substring and
should return an array containing all matched places and their
corresponding location details.
For example, if the input is Avenue (Searched string passed to the
function) then Output should be
[
{
"name": "Avenue Cafe",
"street_no": "7S",
"locality": "Three Notch Road",
"postal_code": "20619",
"lat": "36.83",
"long": "119.6"
}, {
"name": "Avenue Bakery Cafe",
"street_no": "60H",
"locality": "Solomos Island Road",
"postal_code": "20688",
"lat": "36.7783 N",
"long": "119.4179 W"
}
]
You can define the given 2 data sets inside your function. Following is a
sample function skeleton
function findCaliforniaCafes('search string') {
// You can store the given arrays in 2 internal variables
const cafes = [{...}];
const places = [{...}];
// Your code goes here
return results
}
>>>>>>> master
