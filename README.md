public class BookingRequest {
    private String guestName;
    private String roomType;
    private int numberOfRooms;

    public BookingRequest(String guestName, String roomType, int numberOfRooms) {
        this.guestName = guestName;
        this.roomType = roomType;
        this.numberOfRooms = numberOfRooms;
    }

    public String getGuestName() {
        return guestName;
    }

    public String getRoomType() {
        return roomType;
    }

    public int getNumberOfRooms() {
        return numberOfRooms;
    }

    @Override
    public String toString() {
        return "BookingRequest{" +
                "guestName='" + guestName + '\'' +
                ", roomType='" + roomType + '\'' +
                ", numberOfRooms=" + numberOfRooms +
                '}';
    }
}
