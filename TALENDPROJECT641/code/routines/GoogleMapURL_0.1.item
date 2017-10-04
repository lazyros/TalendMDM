// template routine Java
package routines;

/*
 * user specification: the function's comment should contain keys as follows: 1. write about the function's comment.but
 * it must be before the "{talendTypes}" key.
 * 
 * 2. {talendTypes} 's value must be talend Type, it is required . its value should be one of: String, char | Character,
 * long | Long, int | Integer, boolean | Boolean, byte | Byte, Date, double | Double, float | Float, Object, short |
 * Short
 * 
 * 3. {Category} define a category for the Function. it is required. its value is user-defined .
 * 
 * 4. {param} 's format is: {param} <type>[(<default value or closed list values>)] <name>[ : <comment>]
 * 
 * <type> 's value should be one of: string, int, list, double, object, boolean, long, char, date. <name>'s value is the
 * Function's parameter name. the {param} is optional. so if you the Function without the parameters. the {param} don't
 * added. you can have many parameters for the Function.
 * 
 * 5. {example} gives a example for the Function. it is optional.
 */
public class GoogleMapURL {

    /**
     * getURL: return a Google Map URL from the latitude and longitude.
     * 
     * 
     * {talendTypes} String
     * 
     * {Category} User Defined
     * 
     * {param} double(42.231444) input: The latitude.
     * 
     * {example} getURL(42.231444,-71.70523,"&z=9") # http://maps.google.com/maps?q=42.231444,-71.70523&ll=42.231444,-71.70523&z=9
     */
    public static String getURL(Double latitude, Double longitude, String extraArgs) {
        return String.format("http://maps.google.com/maps?q=%s,%s&ll=%s,%s%s", latitude, longitude, latitude, longitude, extraArgs);
    }
}
