import java.util.Arrays;

class longest_Con_seq
{
    public static void main(String[] args)
     {
        int [] a = {102,100,101,3,2,1,1,2,101};
        int n = longest_consecutive(a);
        System.out.println(n);
    }

            // ------------------- Solving Method -------------------//

    static int longest_consecutive(int[] n)
    {
                Arrays.sort(n);         // sorting
        int longest = 0;
        int current = 1;

        for(int i=1; i<n.length; i++)
        {
            if(n[i] != n[i-1])                // if(!Objects.equals(n[i], n[i-1]))

            {
                if(n[i] == n[i-1]+1)           // if(Objects.equals(n[i], n[i-1]+1))
                
                {
                    current++;
                }
                else
                {
                    longest = current;       //Math.max(longest, current);

                    current = 1;
                }
            }

        }
        return longest;
    }
}
