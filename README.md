# Sorting-the-string-variables-

class Sort implements Comparator<String>{

    public int compare(String s1, String s2){

        return s1.compareTo(s2);

    }

}

class code{

    public static void main(String ... args){

        ArrayList<String> n= new ArrayList<String>();

        n.add("Chaitra");

        n.add("Bhumika");

        n.add("Neha");

        n.add("Abhi");

        n.add("Meghna");

        n.add("Chaitra");

        n.sort(new Sort());

        System.out.println(n);

    }

}

/*

[Abhi, Bhumika, Chaitra, Chaitra, Meghna, Neha]

 */
