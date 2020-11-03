# webComponents

Τα WebComponents απλά web micro apps σχεδιάζονται μέσα στις Soft1 προβολές σε Panel "Ειδικής περιοχής" με την ένδειξη HTMLCODE στον Editor.

Λειτουργούν με τον ίδιο τρόπο τόσο μέσα στο Soft1 όσο και στο S360.

Include script : 
<script type="text/javascript" src="XCon.js"></script>

Μέθοδοι : 
1. XCon.setOnDataChange(scope, CallBackFunc);
2. XCon.getData(scope, command, CallBackFunc);
3. XCon.setData(scope, command, CallBackFunc);
4. XCon.openurl(command);
5. XCon.WSCall(scope, uri_path, raw_json_data, CallBackFunc); 
