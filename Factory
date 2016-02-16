# projekt-51
package de.tudarmstadt.fop.project;

public interface Factory {
	
	public abstract class MazeGame {
	    public MazeGame() {
	        Room room1 = makeRoom();
	        Room room2 = makeRoom();
	        room1.connect(room2);
	        this.addRoom(room1);
	        this.addRoom(room2);
	    }

	    abstract protected Room makeRoom();
	}
