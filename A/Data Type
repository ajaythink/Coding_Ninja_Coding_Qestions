import java.util.*;
public class Solution {
    public static int dataTypes(String type) {
        int ans = 0;
        String s = type.toLowerCase();
        String i = "integer";
        String l = "long";
        String f = "float";
        String d = "double";
        String c = "character";
        if(s.equals(l) || s.equals(d)){
            ans = 8;
        }
        else if(s.equals(i) || s.equals(f)){
            ans = 4;
        }
        else{
            ans = 1;
        }
        return ans;
    }
}
