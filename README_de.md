<h1>Leiterplatten in Autodesk Fusion 360 erstellen</h1>
<img src="/resources/00_00.gif" style="width: 600px;" />
<ol>
    <h2>Schaltplan</h2>
    <h3>Vorbereitung</h3>
    <li>
        Unter <b>Datei</b> wählen Sie <b>Neuer Elektronikentwurf</b>:<br />
        <img src="/resources/01_00.png" style="width: 350px;" />
    </li><br />
    <li>
        Fusion 360 wechselt zum Arbeitsbereich <b>Elektronikentwurf</b>, wo Sie einen neuen Schaltplan erstellen müssen (Reiter <b>Allgemein</b>):<br />
        <img src="/resources/02_00.png" style="width: 350px;" />
    </li><br />
    <li>
        Fusion 360 wechselt zum Arbeitsbereich <b>Schaltplan</b>.<br />
        Aktivieren Sie die <b>Komponenten platzieren</b> Gruppe innerhalb der Informationsgruppen, falls diese noch nicht aktiviert ist:<br />
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
                Es stehen Hunderte von Komponentenbibliotheken zur Auswahl. Um eine Vorschau der in einer Bibliothek enthaltenen Komponenten und Packages zu erhalten, können Sie sie entweder auf <b>Library.io</b> anzeigen lassen oder sie herunterladen, um eine Vorschau direkt vom <b>Bibliotheksmanager</b> aus anzuzeigen.<br />
                In diesem Beispiel werden wir jedoch eine lokale Bibliothek importieren (Dateierweiterung <b>.lbr</b>):<br />
                <img src="/resources/05.2_00.png" style="width: 600px;" />
            </li>
            <li>
                Sie können die aktiven Komponentenbibliotheken filtern, um Komponenten auszublenden, die Sie nicht benötigen:<br />
                <img src="/resources/05.3_00.png" style="width: 450px;" />
            </li>
            <li>
                Einige Komponenten haben mehrere Varianten/Packages (angezeigt durch eine nach unten gerichtete Pfeilspitze in der <b>Variante</b> Spalte).<br />
                Durch Klicken auf das Varianten-Feld wird eine Dropdown-Liste geöffnet, die auch eine Vorschau des Footprints und des 3D-Modells zeigt.<br />
                Bevor Sie eine Komponente platzieren, stellen Sie sicher, dass Sie die richtige Variante auswählen, um später mühsame Arbeit zu vermeiden:<br />
                <img src="/resources/05.4_00.png" style="width: 450px;" />
            </li>
        </ol>
    </li><br />
    <h3>Platzieren und Bearbeiten von Komponenten</h3>
		<li>
				Die Platzierung erfolgt standardmäßig am Raster.<br />
        Sie können die <b>Rastereinstellungen</b> nach Ihren Wünschen anpassen (Reiter <b>Entwurf</b>, Tastenkürzel <b>G</b>):<br />
        <img src="/resources/03_00.png" style="height: 300px;" />
        <img src="/resources/03_01.png" style="height: 300px;" />
        Drücken und halten Sie <b>Alt</b> für präzisere Kontrolle.<br />
		</li>
    <h4>Platzieren</h4>
    <li>
        Zum Platzieren einer Komponente doppelklicken Sie auf diese in der <b>Komponente platzieren</b> Gruppe, um in den Komponentenplatzierungsmodus zu gelangen.
        <ol>
            <li>
                Sie können Komponenten durch Rechtsklick drehen und mit der mittleren Maustaste spiegeln (alternativ verwenden Sie die entsprechenden Schaltflächen des <b>Hinzufügen</b>-Fenster):<br />
                <img src="/resources/06.2_00.gif" style="width: 400px;" />
                <img src="/resources/06.2_01.gif" style="width: 400px;" />
            </li>
            <li>
                Klicken Sie mit der linken Maustaste in den Ansichtsbereich, um eine Komponente an der gewünschten Position zu platzieren:<br />
                <img src="/resources/06.1_00.gif" style="width: 600px;" />
            </li>
            <li>
                Um bereits platzierte Komponenten zu verschieben, klicken und halten Sie das Kreuz des entsprechenden Objekts.<br />
                Die Koordinaten des Mauszeigers werden übrigens in der Symbolleiste angezeigt:<br />
                <img src="/resources/06.3_00.gif" style="width: 600px;" />
            </li>
        </ol>
    </li><br />
    <h4>Bearbeiten</h4>
    <li>
        Um den Wert einer platzierten Komponente zu ändern, aktivieren Sie das Werkzeug <b>Wert</b> (Reiter <b>Entwurf</b>, Tastenkürzel <b>V</b>):<br />
        <img src="/resources/07_00.png" style="height: 250px;" />
        <img src="/resources/07_01.gif" style="height: 250px;" />
    </li><br />
    <li>
        Sie können das Package von platzierten Komponenten ändern, indem Sie mit der rechten Maustaste auf diese klicken und <b>Package</b> im Kontextmenü auswählen:<br />
        <img src="/resources/08_00.gif" style="height: 600px;" />
    </li><br />
    <li>
        Sie können auch eine platzierte Komponente durch eine aus einer anderen Komponentenbibliothek ersetzen, indem Sie mit der rechten Maustaste auf diese klicken und <b>Ersetzen</b> im Kontextmenü auswählen:<br />
        <img src="/resources/09_00.gif" style="height: 600px;" />
    </li><br />
    <h3>Netz zeichnen</h3>
    <li>
        Um Komponenten zu verbinden, aktivieren Sie das Werkzeug <b>Netz</b> (Reiter <b>Entwurf</b>, Tastenkürzel <b>R</b>):<br />
        <img src="/resources/10_00.png" style="width: 600px;" /><br />
        Ein Kreis markiert verfügbare Endpunkte, ein Verbindungspunkt zeigt an, dass die Linien Teil derselben Verbindung sind:<br />
        <img src="/resources/10_01.gif" style="width: 600px;" />
    </li><br />
    <h2>Leiterplatte</h2>
    <li>
        Sobald Sie bereit sind, Ihre Leiterplatte zu entwerfen, wechseln Sie zum Arbeitsbereich <b>Leiterplattendokument</b> (Reiter <b>Entwurf</b>):<br />
        <img src="/resources/11_00.png" style="width: 400px;" />
        <img src="/resources/11_01.png" style="width: 600px;" />
    </li><br />
	<h3>Vorbereitung</h3>
    <h4>Leiterplattenform</h4>
    <li>
        In den meisten Fällen möchten Sie wahrscheinlich die Dimensionen Ihrer Leiterplatte ändern oder genau definieren, bevor Sie Komponenten platzieren.<br />
        Es gibt mehrere Möglichkeiten, dies zu tun:<br /><br />
&nbsp&nbsp&nbsp&nbsp
          a) Für schnelle und einfache Anpassungen ziehen und verschieben Sie einfach die Kontur der Leiterplatte, um ihre Form zu ändern:<br />
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
            <img src="/resources/12.a_00.gif" style="width: 600px;" /><br />
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
            Sie können die Leiterplattenform auch zusätzlich mit den <b>Leiterplattenform</b> Werkzeugen ändern (Reiter <b>Entwurf</b>).<br /><br />
&nbsp&nbsp&nbsp&nbsp
          b) In den meisten Fällen möchten Sie jedoch wahrscheinlich die Dimensionen Ihrer Leiterplatte genauer definieren:<br />
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
              1. Klicken Sie zunächst auf die Schaltfläche <b>Auf 3D-Leiterplatte übertragen</b> (Reiter <b>Entwurf</b>):<br />
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
                <img src="/resources/12.b.1_00.png" style="height: 300px;" />
                <img src="/resources/12.b.1_01.png" style="height: 300px;" /><br /><br />
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
              2. Fusion 360 wechselt zum Arbeitsbereich <b>3D-Leiterplatte</b>, wo Sie die Skizze <b>Outline</b> bearbeiten müssen:<br />
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp;&nbsp;&nbsp;
                <img src="/resources/12.b.2_00.png" style="height: 400px;" />
                <img src="/resources/12.b.2_01.gif" style="height: 400px;" /><br /><br />
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
              3. Sobald Sie mit der Bearbeitung der Skizze fertig sind, klicken Sie auf die Schaltfläche <b>Auf 2D-Leiterplatte übertragen</b>, um beide Arbeitsbereiche erneut zu synchronisieren (Reiter <b>3D-Leiterplatte</b>):<br />
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp;&nbsp;&nbsp;
                <img src="/resources/12.b.3_00.png" style="width: 350px;" />
    </li><br />
    <h4>GND-Layer</h4>
    <li>
        Zurück im Arbeitsbereich <b>Leiterplattendokument</b> können Sie nun ein GND-Layer erstellen.
        <ol>
            <li>
                Wählen Sie die Kontur der Leiterplatte aus, klicken Sie mit der rechten Maustaste auf eine der Linien und wählen Sie unter <b>In Linien konvertieren</b> <b>Kopieren</b> aus. Wählen Sie im <b>Layer</b>-Fenster Ebene <b>#16 Bottom</b> aus:<br />
                <img src="/resources/13.1_00.gif" style="width: 1000px;" />
            </li>
            <li>
                Wählen Sie aus der Sektion <b>Ändern</b> des Reiters <b>Entwurf</b> das Werkzeug <b>Name</b> (Tastenkürzel <b>N</b>) und klicken Sie auf die Kontur der Leiterplatte. Geben Sie schließlich im <b>Name</b>-Fenster "GND" ein:<br />
                <img src="/resources/13.2_00.gif" style="width: 1000px;" />
            </li>
        </ol>
    </li><br />
	<h4>Layer</h4>
    <li>
        Bevor Sie Komponenten platzieren, stellen Sie sicher, dass das richtige Layer aktiviert ist (in diesem Fall <b>#1 Top</b>):<br />
        <img src="/resources/14_00.png" style="width: 600px;" /><br />
        <ol>
            <li>
                Für komplexere Leiterplatten können Sie außerdem den <b>Ebenen-Manager</b> verwenden (Reiter <b>Entwurf</b>):<br />
                <img src="/resources/14.1_00.png" style="width: 400px;" />
                <img src="/resources/14.1_01.png" style="width: 600px;" />
            </li>
        </ol>
    </li><br />
    <h3>Platzieren und Bearbeiten von Komponenten</h3>
    <li>
        Die Steuerungen zum Platzieren und Bearbeiten von Komponenten ähneln dem Arbeitsbereich <b>Schaltplan</b>:<br />
        <img src="/resources/14.2_00.gif" style="width: 1000px;" />
    </li>
    <h3>Verlegen</h3>
    <li>
        Sobald Sie alle Komponenten platziert haben, müssen Sie die Verbindungen verlegen. Auch hier stehen Ihnen mehrere Optionen zur Auswahl.
        <ol>
            <li>
                Für volle Kontrolle können Sie alle Verbindungen <b>Manuell verlegen</b> (Reiter <b>Entwurf</b>, Tastenkürzel <b>R</b>):<br />
                <img src="/resources/15.1_00.png" style="width: 400px;" />
                <img src="/resources/15.1_01.gif" style="width: 1000px;" />
            </li>
            <li>
                Jedoch ist wesentlich zeiteffizienterer den <b>AutoRouter</b> unter Sektion <b>Schnellverlegung</b> zu verwenden (Reiter <b>Entwurf</b>):<br />
                <img src="/resources/15.2_00.png" style="width: 400px;" />
                <img src="/resources/15.2_01.gif" style="width: 1000px;" />
            </li>
        </ol>
    </li>
    <h2>3D-Leiterplatte</h2>
    <li>
        Um Ihre fertige Leiterplatte in 3D anzusehen, klicken Sie erneut auf die Schaltfläche <b>Auf 3D-Leiterplatte übertragen</b>.<br />
        Sie werden feststellen, dass Komponenten ohne 3D-Modelle als Rechtecke dargestellt werden:<br />
        <img src="/resources/16_00.png" style="width: 1000px;" /><br />
        Blenden Sie <b>Packages</b> aus, um alle Komponenten auszublenden und einen Blick auf die rohe Leiterplatte zu werfen:<br />
        <img src="/resources/16_01.png" style="width: 1000px;" /><br />
    </li>
    <h2>Exportieren</h2>
    <li>
        Falls Sie Ihre Leiterplatte exportieren möchten (z. B. um sie von einem Leiterplattenhersteller zu bestellen), wechseln Sie zurück zum Arbeitsbereich <b>Leiterplattendokument</b>, aktivieren Sie den Reiter <b>Fertigung</b> und klicken auf die Schaltfläche <b>Gerber-, NC-Bohrer-, Baugruppen- und Zeichnungsausgaben exportieren</b>:<br />
        <img src="/resources/17_00.png" style="height: 350px;" />
        <img src="/resources/17_01.png" style="height: 350px;" /><br />
        <img src="/resources/17_02.png" style="width: 800px;" /><br />
    </li>
</ol>
