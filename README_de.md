<h1>Wie man eine Leiterplatte in Autodesk Fusion 360 entwirft</h1>
<img src="/resources/00_00.gif" style="width: 600px;" />
<ol>
    <h2>Schaltplan</h2>
    <h3>Vorbereitung</h3>
    <li>
        Unter <b>Datei</b> wählen Sie <b>Neues Elektronikdesign</b>:<br />
        <img src="/resources/01_00.png" style="width: 350px;" />
    </li><br />
    <li>
        Fusion wechselt zum <b>Elektronikdesign</b>-Arbeitsbereich, wo Sie einen neuen Schaltplan erstellen müssen (<b>Allgemein</b> tab):<br />
        <img src="/resources/02_00.png" style="width: 350px;" />
    </li><br />
    <li>
        Fusion wechselt zum <b>Schaltplan</b>-Arbeitsbereich. Die Platzierung erfolgt standardmäßig am Gitter, drücken und halten Sie <b>Alt</b> für feinere Kontrolle.<br />
        Sie können die <b>Gittereinstellungen</b> nach Ihren Wünschen anpassen (<b>Entwurf</b> tab, Hotkey <b>G</b>):<br />
        <img src="/resources/03_00.png" style="height: 300px;" />
        <img src="/resources/03_01.png" style="height: 300px;" />
    </li><br />
    <li>
        Aktivieren Sie das <b>Komponenten platzieren</b>-Panel innerhalb des Informationspanels, falls es noch nicht aktiviert ist:<br />
        <img src="/resources/04_00.png" style="width: 450px;" />
    </li><br />
    <h4>Bibliotheken</h4>
    <li>
        Stellen Sie vor dem Platzieren von Komponenten sicher, dass die erforderlichen Komponentenbibliotheken aktiviert sind.
        <ol>
            <li>
                Öffnen Sie den <b>Bibliotheksmanager</b>:<br />
                <img src="/resources/05.1_00.png" style="width: 450px;" />
            </li>
            <li>
                Es gibt Hunderte von Komponentenbibliotheken zur Auswahl. Um eine Vorschau der enthaltenen Komponenten und Pakete zu erhalten, können Sie sie entweder auf <b>Library.io</b> anzeigen oder sie herunterladen, um eine Vorschau direkt vom <b>Bibliotheksmanager</b> aus anzuzeigen.<br />
                In diesem Beispiel werden wir jedoch eine lokale Bibliothek importieren (Dateierweiterung <b>.lbr</b>):<br />
                <img src="/resources/05.2_00.png" style="width: 600px;" />
            </li>
            <li>
                Sie können die aktiven Komponentenbibliotheken filtern, um Komponenten auszublenden, die Sie nicht benötigen:<br />
                <img src="/resources/05.3_00.png" style="width: 450px;" />
            </li>
            <li>
                Einige Komponenten haben mehrere Varianten/Pakete (angezeigt durch einen nach unten zeigenden Pfeil im <b>Variant</b>-Feld).<br />
                Durch Klicken auf das Variantenfeld wird eine Dropdown-Liste geöffnet, die auch eine Vorschau des Footprints und des 3D-Modells zeigt.<br />
                Bevor Sie eine Komponente platzieren, stellen Sie sicher, dass Sie die richtige Variante auswählen, um späteren Ärger zu vermeiden:<br />
                <img src="/resources/05.4_00.png" style="width: 450px;" />
            </li>
        </ol>
    </li><br />
    <h3>Platzieren und Bearbeiten von Komponenten</h3>
    <h4>Platzieren</h4>
    <li>
        Um eine Komponente zu platzieren, doppelklicken Sie darauf im <b>Komponente platzieren</b>-Panel, um in den Komponentenplatzierungsmodus zu gelangen.
        <ol>
            <li>
                Klicken Sie im Canvas, um eine Komponente an der gewünschten Position zu platzieren:<br />
                <img src="/resources/06.1_00.gif" style="width: 600px;" />
            </li>
            <li>
                Sie können Komponenten durch Rechtsklick drehen und mit der mittleren Maustaste spiegeln (alternativ verwenden Sie die entsprechenden Schaltflächen des <b>Hinzufügen</b>-Dialogs):<br />
                <img src="/resources/06.2_00.gif" style="width: 400px;" />
                <img src="/resources/06.2_01.gif" style="width: 400px;" />
            </li>
            <li>
                Um bereits platzierte Objekte zu verschieben, klicken und halten Sie das Kreuz des entsprechenden Objekts.<br />
                Die Koordinaten des Mauszeigers werden auch in der Symbolleiste angezeigt:<br />
                <img src="/resources/06.3_00.gif" style="width: 600px;" />
            </li>
        </ol>
    </li><br />
    <h4>Bearbeiten</h4>
    <li>
        Um den Wert einer platzierten Komponente zu ändern, aktivieren Sie das <b>Wert</b>-Werkzeug (<b>Entwurf</b> tab, Hotkey <b>V</b>):<br />
        <img src="/resources/07_00.png" style="height: 250px;" />
        <img src="/resources/07_01.gif" style="height: 250px;" />
    </li><br />
    <li>
        Sie können das Gehäuse von platzierten Komponenten ändern, indem Sie mit der rechten Maustaste darauf klicken und <b>Gehäuse</b> im Kontextmenü auswählen:<br />
        <img src="/resources/08_00.gif" style="height: 600px;" />
    </li><br />
    <li>
        Sie können auch eine platzierte Komponente durch eine aus einer anderen Komponentenbibliothek ersetzen, indem Sie mit der rechten Maustaste darauf klicken und <b>Ersetzen</b> im Kontextmenü auswählen:<br />
        <img src="/resources/09_00.gif" style="height: 600px;" />
    </li><br />
    <h3>Netz zeichnen</h3>
    <li>
        Um Komponenten zu verbinden, aktivieren Sie das <b>Netz</b>-Werkzeug (<b>Entwurf</b> tab, Hotkey <b>R</b>):<br />
        <img src="/resources/10_00.png" style="width: 600px;" /><br />
        Ein Kreis markiert verfügbare Endpunkte, ein Verbindungspunkt zeigt an, dass die Linien Teil derselben Verbindung sind:<br />
        <img src="/resources/10_01.gif" style="width: 600px;" />
    </li><br />
    <h2>Leiterplatte (PCB)</h2>
    <li>
        Sobald Sie bereit sind, Ihre Leiterplatte zu entwerfen, wechseln Sie zum <b>Leiterplattendokument</b>-Arbeitsbereich (<b>Entwurf</b> tab):<br />
        <img src="/resources/11_00.png" style="width: 400px;" />
        <img src="/resources/11_01.png" style="width: 600px;" />
    </li><br />
	<h3>Vorbereitung</h3>
    <h4>PCB-Umriss</h4>
    <li>
        In den meisten Fällen möchten Sie wahrscheinlich die Abmessungen Ihrer Leiterplatte ändern oder definieren, bevor Sie Komponenten platzieren.<br />
        Es gibt mehrere Möglichkeiten, dies zu tun:<br /><br />
&nbsp&nbsp&nbsp&nbsp
          a) Für schnelle und einfache Anpassungen ziehen und verschieben Sie einfach die Umrisse der Leiterplatte, um ihre Form zu ändern:<br />
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
            <img src="/resources/12.a_00.gif" style="width: 600px;" /><br />
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
            Sie können den Leiterplattenumriss auch weiter mit den <b>Leiterplattenform</b>-Werkzeugen ändern.<br /><br />
&nbsp&nbsp&nbsp&nbsp
          b) In den meisten Fällen möchten Sie jedoch wahrscheinlich die Abmessungen Ihrer Leiterplatte genauer definieren:<br />
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
              1. Zuerst <b>Zu 3D-PCB verschieben</b> (<b>Entwurf</b> tab):<br />
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
                <img src="/resources/12.b.1_00.png" style="height: 300px;" />
                <img src="/resources/12.b.1_01.png" style="height: 300px;" /><br /><br />
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
              2. Fusion wechselt zum <b>3D-PCB</b>-Arbeitsbereich, wo Sie den Umriss des Sketches bearbeiten müssen:<br />
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp;&nbsp;&nbsp;
                <img src="/resources/12.b.2_00.png" style="height: 400px;" />
                <img src="/resources/12.b.2_01.gif" style="height: 400px;" /><br /><br />
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
              3. Sobald Sie mit der Bearbeitung des Sketches fertig sind, <b>Zu 2D-PCB verschieben</b>, um beide Arbeitsbereiche erneut zu synchronisieren (<b>3D-PCB</b> tab):<br />
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp;&nbsp;&nbsp;
                <img src="/resources/12.b.3_00.png" style="width: 350px;" />
    </li><br />
    <h4>GND-Plane</h4>
    <li>
        Zurück im Leiterplattendokument-Arbeitsbereich können Sie wählen, eine GND-Plane zu erstellen.
        <ol>
            <li>
                Wählen Sie die Umrisslinien der Leiterplatte aus, klicken Sie mit der rechten Maustaste auf eine der Linien und wählen Sie unter <b>In Polygon umwandeln</b> <b>Kopie</b> aus. Wählen Sie im <b>Ebene</b>-Dialog Ebene <b>#16 Bottom</b>:<br />
                <img src="/resources/13.1_00.gif" style="width: 1000px;" />
            </li>
            <li>
                Wählen Sie aus dem <b>Bearbeiten</b>-Abschnitt des <b>Bearbeiten</b>-Tabs das <b>Name</b>-Werkzeug (Hotkey <b>N</b>) und klicken Sie auf den Umriss der Leiterplatte. Geben Sie schließlich im <b>Name</b>-Dialog "GND" ein:<br />
                <img src="/resources/13.2_00.gif" style="width: 1000px;" />
            </li>
        </ol>
    </li><br />
	<h4>Ebenen</h4>
    <li>
        Bevor Sie Komponenten platzieren, stellen Sie sicher, dass die richtige Ebene aktiviert ist (in diesem Fall <b>#1 Top</b>):<br />
        <img src="/resources/14_00.png" style="width: 600px;" /><br />
        <ol>
            <li>
                Für komplexere Leiterplatten möchten Sie möglicherweise den <b>Ebenen-Manager</b> verwenden (<b>Entwurf</b> tab):<br />
                <img src="/resources/14.1_00.png" style="width: 400px;" />
                <img src="/resources/14.1_01.png" style="width: 600px;" />
            </li>
        </ol>
    </li><br />
    <h3>Platzieren und Bearbeiten von Komponenten</h3>
    <li>
        Die Steuerungen zum Platzieren und Bearbeiten von Komponenten ähneln dem <b>Schaltplan</b>-Arbeitsbereich:<br />
        <img src="/resources/14.2_00.gif" style="width: 1000px;" />
    </li>
    <h3>Routing</h3>
    <li>
        Sobald Sie alle Komponenten platziert haben, müssen Sie die Verbindungen routen. Auch hier stehen Ihnen mehrere Optionen zur Auswahl.
        <ol>
            <li>
                Für volle Kontrolle können Sie alle Verbindungen manuell routen (<b>Entwurf</b> tab, Hotkey <b>R</b>):<br />
                <img src="/resources/15.1_00.png" style="width: 400px;" />
                <img src="/resources/15.1_01.gif" style="width: 1000px;" />
            </li>
            <li>
                Jedoch ist ein wesentlich zeiteffizienterer Weg die Verwendung des Autorouters (<b>Entwurf</b> tab):<br />
                <img src="/resources/15.2_00.png" style="width: 400px;" />
                <img src="/resources/15.2_01.gif" style="width: 1000px;" />
            </li>
        </ol>
    </li>
    <h2>3D-PCB</h2>
    <li>
        Um Ihre fertige Leiterplatte in 3D anzusehen, <b>Zu 3D verschieben</b> Sie erneut.<br />
        Sie werden feststellen, dass Komponenten ohne 3D-Modelle als Rechtecke dargestellt werden:<br />
        <img src="/resources/16_00.png" style="width: 1000px;" /><br />
        Blenden Sie <b>Pakete</b> aus, um alle Komponenten auszublenden und einen Blick auf die nackte Leiterplatte zu werfen:<br />
        <img src="/resources/16_01.png" style="width: 1000px;" /><br />
    </li>
    <h2>Exportieren</h2>
    <li>
        Schließlich, wenn Sie Ihre Leiterplatte exportieren möchten (z. B. um sie von einem Leiterplattenhersteller zu bestellen), wechseln Sie zurück zum <b>Leiterplattendokument</b>-Arbeitsbereich, aktivieren Sie den <b>Fertigung</b> tab und <b>Exportieren Sie Gerber, NC-Bohrungen, Montage- und Zeichnungsausgaben</b>:<br />
        <img src="/resources/17_00.png" style="height: 350px;" />
        <img src="/resources/17_01.png" style="height: 350px;" /><br />
        <img src="/resources/17_02.png" style="width: 800px;" /><br />
    </li>
</ol>
