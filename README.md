# ECTE-331
package drone;

import java.io.IOException;

/**
 * Custom exception representing a sensor hardware failure.
 * Thrown when a sensor cannot produce a reading due to a fault.
 * Extends IOException because sensor communication is treated as I/O.
 *
 * @author Student
 * @version 1.0
 */
public class SensorReadException extends IOException {

    /**
     * Constructs a SensorReadException with a detail message.
     * @param message description of the sensor failure
     */
    public SensorReadException(String message) {
        super(message);
    }

} // class SensorReadException
