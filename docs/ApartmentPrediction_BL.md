// java class

public class Apartment {
        private String id;
        private Long price;
        private Integer area;
        private Integer bedrooms;
        private Integer bathrooms;
        private Integer stories;
        private String mainroad;
        private String guestroom;
        private String basement;
        private String hotwater;
        private String heating;
        private String airconditioning;
        private Integer parking;
        private String prefarea;
        private String furnishingstatus;      

        private List <Post>;
        private Owner <owner>;    
    }


public class Owner {
        private String id;
        private String name;
        private String lastName;
        private String phone;
        private List<Apartment>;
        private String email;
}

public class Reviewer {
        private String id;
        private String name;
        private String lastName;
        private String phone;
        private List<Post>;
        private String email;
}

public class Post {
        private String id;
        private String message;
        private int rate;
        private Reviewer author;
        private LocalDate publicationDate;
}
