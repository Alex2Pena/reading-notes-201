# Local Storage (Lecture)

1.Data Persistance *Must be able to:*
- C - Create - setItem(key, value)
- R - Read - getItem(key)
- U - Update - setItem(key, (new)value)
- D - Delete - removeItem(key)
- clear() *rare* - Clears **ALL** local storage - (empty)

1. Is the browsers database (think cookies & chache...)
- cookies limit to 4kbps
- local storage is 5Mbps
- uses key:value association

1. JSON - JavaScript Object Notation
- "Stringify" object to sore in local storage
function updateStorage(){
    var arrayString = JSON.stringify(array.name)
    localStorage.setItem(key,value)
}
- "Parse" object to grab from local storage
function getFromStorage(){
    var retreive = 
}