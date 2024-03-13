# 1.API ir Application Programming Interface, kas ļauj programmētājiem izmantot citu programmu vai pakalpojumu funkcionalitāti savās aplikācijās, nodrošinot komunikāciju un datu apmaiņu starp tām.
# 2.Mainīgo PHP valodā var deklarēt, izmantojot dollāra zīmi, piemēram:   $mainigais = vērtība;
# 3.Laravel izmanto MVC (Model-View-Controller) arhitektūru. Modelis atbild par datu glabāšanu un manipulāciju, Skats par datu attēlošanu lietotājam un Kontrolieris par darbību apstrādi un starpniecību starp modeļiem un skatiem.
# 4.ORM (Object-Relational Mapping) ir tehnoloģija, kas ļauj programmētājiem# darboties ar datubāzes ierakstiem kā objektiem. To izmanto, lai atvieglotu datu bāzes pieprasījumu veidošanu un pārvaldīšanu, kas samazina tīras SQL sintakses nepieciešamību.

# 5.Eloquent ORM pieprasījums modelim User, lai iegūtu visus lietotājus ar reitingu lielāku par 4, varētu izskatīties šādi: $lietotaji = User::where('reitings', '>', 4)->get();
# Tabulas struktūra būtu kaut kas līdzīgs:

CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    vards VARCHAR(255),
    uzvards VARCHAR(255),
    reitings INT
);
