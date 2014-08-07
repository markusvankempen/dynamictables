dynamictables
=============

dynamic table/parameter display uising ui5 and json

 * 
* This program display the export and table json parameters dynamically
* Author: Markus van Kempen - mvk@ca.ibm.com
*
data/json structure is like (sap/mfcall/ZMVKRFCEXAMPLE?format=json)
{
    "EXPORTPARA1": "Hello",
    "EXPORTPARA2": "World",
    "BIGSTRUCTURETBL": [
        {
            "FIELDNAME1": "TABREC11",
            "FIELDNAME2": "TABREC12",
            "FIELDNAME3": "TABREC13",
            "FIELDNAME4": "TABREC14",
            "FIELDNAME5": "TABREC15",
            "FIELDNAME6": "TABREC16",
            "FIELDNAME7": "TABREC17",
            "FIELDNAME8": "TABREC18"
        }
    ],
    "DATATBL": [
        {
            "FIELDNAME1": "VALUE 11",
            "FIELDNAME2": "VALUE 12"
        },
        {
            "FIELDNAME1": "VALUE 21",
            "FIELDNAME2": "VALUE 22"
        },
        {
            "FIELDNAME1": "VALUE 31",
            "FIELDNAME2": "VALUE 32"
        },
        {
            "FIELDNAME1": "VALUE 41",
            "FIELDNAME2": "VALUE 42"
        }
    ]
}
 Note: Table with one entry are displayed in two columns one with Key(fieldname) and one with Values
