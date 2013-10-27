class Fraccion
attr_reader :numerador, :denominador

	def initialize (numerador,denominador)
                @numerador=numerador
                @denominador=denominador    
        end

	def gcd(u, v)
        	u, v = u.abs, v.abs
         	while (v!=0)
         	       u, v = v, u % v
      	    	end
       	   	u	
    	end

        def fraccion_Reducida
        	@mcd=gcd(@numerador,@denominador)
        	@numerador=@numerador/@mcd
       	 	@denominador=@denominador/@mcd
        	Fraccion.new(@numerador,@denominador)        
     	end
	
	def num
                num=@numerador
                num	
	end
        
        def den
                den=@denominador
                den
        end

	def to_s
   	 	"#{@numerador}/#{@denominador}"
    	end
    
   	def to_f
   	 	"#{Float(@numerador)/@denominador}"
    	end

	def ==(obj2)
	   	 if @numerador == obj2.numerador
	   		 if @denominador == obj2.denominador
	   			 return true
	   		 end
	   	 else
	   		 return false
	   	 end
	    end
    
	def absoluto
	   	 @numerador.abs
	   	 @denominador.abs
	   	 Fraccion.new(@numerador,@denominador)    
	end

    	def reciprocal
   		 @aux=@numerador
   		 @numerador=@denominador
   		 @denominador=@aux
   		 Fraccion.new(@numerador,@denominador)    
    	end
    
    	def opuesto
   		 @numerador=@numerador *(-1)
   		 Fraccion.new(@numerador,@denominador)    
    	end

end
