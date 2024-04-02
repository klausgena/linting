## AirBnB Style Guide
- assing vars from object, destructuring:
    const {name, first} = person; // person.name, person.first
    ook voor arrays bv. arr = [1 2 ,3, 4], const [first, second] = arr; // [1, 2]

- bij importeren de bestandsnaamextensie weglaten (dus zonder .js)
- beter leren werken met Array map(), reduce() en filter()
- geen num++ of num-- gebruiken, maar num += 1 of num -= 1 ...
- en er is ook zo een [... array] constructie die ik niet helemaal begrijp
- === en !== gebruiken ipv == en !=
- interessante notaties (om ternaire operator te vermijden):
        const foo = a || b;
        const bar = !!c;
        const baz = !c;
        const quux = a ?? b; // als links null is, wordt rechts toegewezen
- als if altijd eindigt op return, dan is er geen else nodig. Als er na een if met return een else if volgt, is dat eigenlijk niet nodig. Een tweede if is hier meer op zijn plaats.
- commentaar van meerdere lijnen, niet // maar /** .... */
- // commentaar voor je onderwerp (boven)
- een lege regel na elke blok laten
- opsomming van vars in functies en eigenschappen van objects: ook het laatste element moet een komma hebben.   
- in klassen geen get en set gebruiken, maar getVal en setVal functies maken, Als Boolean dan isVal of hasVal
- Als je functie meerdere gegevens retourneert, zet ze dan in een object. Dan kan de gebruiker gemakkelijk kiezen wat hij nodig heeft.
- in functie bv. function gG (...args) {} is args een array. Dat heet rest parameters. Iets vergelijkbaar is spreads, [... arr] om arrays te kopieren, bv.