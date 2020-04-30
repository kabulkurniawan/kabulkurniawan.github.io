@prefix : <https://kabulkurniawan.github.io/profile/#>.
@prefix bibo: <http://purl.org/ontology/bibo/>.
@prefix cc: <http://creativecommons.org/ns#>.
@prefix con: <http://www.w3.org/2000/10/swap/pim/contact#>.
@prefix dbo: <http://dbpedia.org/ontology/>.
@prefix dbp: <http://dbpedia.org/resource/>.
@prefix dc: <http://purl.org/dc/terms/>.
@prefix dcat: <http://www.w3.org/ns/dcat#>.
@prefix foaf: <http://xmlns.com/foaf/0.1/>.
@prefix ldp: <http://www.w3.org/ns/ldp#>.
@prefix org: <http://www.w3.org/ns/org#>.
@prefix owl: <http://www.w3.org/2002/07/owl#>.
@prefix pim: <http://www.w3.org/ns/pim/space#>.
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#>.
@prefix schema: <http://schema.org/>.
@prefix solid: <http://www.w3.org/ns/solid/terms#>.
@prefix vcard: <http://www.w3.org/2006/vcard/ns#>.
@prefix wikipedia: <http://en.wikipedia.org/wiki/>.
@prefix xsd: <http://www.w3.org/2001/XMLSchema#>.

# Profile document

<https://kabulkurniawan.github.io/profile/>
    a foaf:Document, foaf:PersonalProfileDocument;
    rdfs:label "Kabul Kurniawan’s FOAF profile"@en;
    foaf:maker :me;
    foaf:primaryTopic :me.

# Personal details

:me a foaf:Person;
    foaf:name  "Kabul Kurniawan"@en, "Kabul Kurniawan"@id;
    rdfs:label "Kabul Kurniawan"@en, "Kabul Kurniawan"@id;
    vcard:fn   "Kabul Kurniawan"@en, "Kabul Kurniawan"@id;
    con:preferredURI "https://kabulkurniawan.github.io/profile/#me";
    foaf:givenName "Kabul"@en, "Kabul"@id;
    foaf:familyName "Kurniawan"@en, "Kurniawan"@id;
    foaf:title "B.Sc., M.Cs."@en, "S.Kom, M.Cs"@id;
    vcard:title "PhD Student/Researcher in Linked Data, Interoperability, Cybersecurity"@en;
    dbo:birthPlace dbp:Pekalongan;
    dbo:birthDate "1987-11-30"^^xsd:date;
    foaf:birthday "11-30";
    foaf:age 32;
    foaf:gender "male"@en;
    dbo:location dbp:Vienna;
    foaf:based_near dbp:Vienna;
    foaf:img <https://kabulkurniawan.github.io/img/kabulkurniawan.png>;
    foaf:mbox <mailto:kabulkurniawan@gmail.com>;
    foaf:homepage <https://kabulkurniawan.github.io/>;
    foaf:weblog <https://ruben.verborgh.org/blog/>;
    foaf:publications <https://ruben.verborgh.org/publications/>;
    foaf:account <https://github.com/kabulkurniawan>,
                 <https://twitter.com/kabulkurniawan>,
                 <https://www.linkedin.com/in/kabulkurniawan/>;
    dbo:orcidId "0000−0002−5353−7376";
    foaf:workplaceHomepage <http://ifs.tuwien.ac.at/>;
    org:memberOf <http://univie.ac.at>,
                 dbp:Vienna_University.