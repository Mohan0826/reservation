# reservation
{
    private HashMap<String, List<Integer>> Lakewood = new HashMap<>();
    private HashMap<String, List<Integer>> Bridgewood = new HashMap<>();
    private HashMap<String, List<Integer>> Ridgewood = new HashMap<>();
    private static int LakewoodRating;
    private static int BridgewoodRating;
    private static int RidgewoodRating;

    public HotalReservation() {
        setLakewood();
        setBridgewood();
        setRidgewood();

    }

    private void setLakewood() {
        List<Integer> lakewoodReward = new ArrayList<>();
        lakewoodReward.add(110);
        lakewoodReward.add(80);

        List<Integer> lakewoodRegular = new ArrayList<>();
        lakewoodRegular.add(110);
        lakewoodRegular.add(90);

        System.out.println("Enter the lakewoodReward price");
        System.out.println("Enter the lakewoodRegular price");
        System.out.println("Enter the lakewoodRating is 3");
    }

    private void setBridgewood() {
        List<Integer> BridgewoodReward = new ArrayList<>();
        BridgewoodReward.add(160);
        BridgewoodReward.add(50);

        List<Integer> BridgewoodRegular = new ArrayList<>();
        BridgewoodRegular.add(160);
        BridgewoodRegular.add(60);

        System.out.println("Enter the BridgewoodReward price");
        System.out.println("Enter the BridgewoodRegular price");
        System.out.println("Enter the lakewoodRating is 4");
    }

    private void setRidgewood() {
        List<Integer> RidgewoodReward = new ArrayList<>();
        RidgewoodReward.add(220);
        RidgewoodReward.add(40);

        List<Integer> RidgewoodRegular = new ArrayList<>();
        RidgewoodRegular.add(220);
        RidgewoodRegular.add(150);

        System.out.println("Enter the RidgewoodReward price");
        System.out.println("Enter the RidgewoodRegular price");
        System.out.println("Enter the RidgewoodRating is 5");
    }

    public String costofHotel(String input) {
        String arr = String.valueOf(input.split(","));
        String CustomerType = "";

    }
}
