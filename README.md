# Application-
Application of homework

package dz.univeloued.tps.Apps;

import dz.univeloued.tps.classes.*;

public class Application {
    public static void main(String[] args) {
        // Création des objets
        Personne p1 = new Personne(1, "Test", "Personne");

        Etudiant e1 = new Etudiant(2, "OBAKA", "Med", "65678754", "Info");
        Etudiant e2 = new Etudiant(3, "KHALFI", "Messoud", "87543543", "Math");

        Employe emp1 = new Employe(4, "DOU", "Rachid", 10000.0);
        Employe emp2 = new Employe(5, "FARH", "Djamel", 10000.0);

        Enseignant prof1 = new Enseignant(6, "OKBA", "Kamal", 67000.0, "JAVA/JEE");
        Enseignant prof2 = new Enseignant(7, "Mohamed", "Cheick", 55000.0, "Mathématique");

        // Affichage
        System.out.println("La liste des employes :");
        System.out.println(emp1);
        System.out.println(emp2);

        System.out.println("La liste des étudiants :");
        System.out.println(e1);
        System.out.println(e2);

        System.out.println("La liste des professeurs :");
        System.out.println(prof1);
        System.out.println(prof2);

        System.out.println("Nb objet de type Personne = " + Personne.getCount());
    }
}
