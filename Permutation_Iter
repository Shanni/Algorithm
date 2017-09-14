// iterate method to write permutation

class Permutation{    
    public static void count(int[] lengthOfDeminsion) { 
    	// Your resolution 
    	int dimension = lengthOfDeminsion.length;
    	int[] indexes = new int[dimension];
    	
    	int curr = 0, ind = 0;
    	long sum = 0;
    	boolean next = true;
    	while(ind != dimension){
    		if(next){
        
          // do whatever for the number:
    			for(int i = 0; i < dimension; i++){
        			System.out.print(indexes[i] + " ");
        		}
        		System.out.println();
    		}
    		
    		if(++indexes[ind] == lengthOfDeminsion[ind]){
    			next = false;
    			ind ++;
    			
    		}else{
    			if(!next){
    				for(int i = 0; i < ind; i++){
    					indexes[i] = 0;
    				}
    				ind = 0;
    			}
    			next = true;
    		}
    	}
   // Time complexity:  O(n) - number of permutation
   // Space complexity: O(k) - length of permutation
    
    }
    public static void main(String[] args){
    	count(new int[]{3,4,5});
    }
}
