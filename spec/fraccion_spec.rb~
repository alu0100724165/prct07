require "lib/fraccion.rb"

describe Fraccion do

      	before :each do
       	        @p1=Fraccion.new(15,30)
       		@p2=Fraccion.new(20,40)
       	end
       	describe "Obtener datos y fraccion reducida" do
       	        it "Se almacena el numerador" do
       	                @p1.numerador.should eq(15)
       	        end
       	        it "Debe existir un denominador" do
       		     	@p1.denominador.should eq(30)
        	end
               	it "La fraccion debe estar reducida" do
                        @p1.fraccion_Reducida.should eq(Fraccion.new(1,2))
        	end
    	end
	describe "Metodos que devuelven al numerador y denominador" do
   		it "Invocar Método para obtener el numerador" do
   		 	@p1.fraccion_Reducida
                    	@p1.num.should eq(1)
            	end
           	it "Invocar Método para obtener el denominador" do
   		 	@p1.fraccion_Reducida                   	 
   		 	@p1.den.should eq(2)
            	end
    	end
	describe "Comparacion de dos fracciones" do
   	 	it "Compara si dos fracciones son iguales" do
   			(@p1==Fraccion.new(15,30)).should eq(true)    
   	 	end
    	end
    	describe "Calcular valor absoluto, reciproco y opuesto de una fraccion" do
   	 	it "Calcular Valor absoluto" do
   			 @p1.fraccion_Reducida   		 
   		 	 @p1.absoluto.should eq(Fraccion.new(1,2))
   	 	end
   	 	it "Calcular reciprocal" do
   			 @p1.fraccion_Reducida
   			 @p1.reciprocal.should eq(Fraccion.new(2,1))   	 
   		end
   		it "Calcular opuesto" do
   			 @p1.fraccion_Reducida
   			 @p1.opuesto.should eq(Fraccion.new(-1,2))   	 
   		end
   	end
	describe "Operaciones" do
        	it "Operacion de suma" do
            		@p1.fraccion_Reducida
            		@p2.fraccion_Reducida    
            		(@p1+@p2).should eq(Fraccion.new(1,1))
        	end
		it "Operacion de resta" do
		    	@p1.fraccion_Reducida
		    	@p2.fraccion_Reducida
		    	(@p1-@p2).should eq(Fraccion.new(0,1))
		end
		it "Operacion de division" do
		    	@p1.fraccion_Reducida
		    	@p2.fraccion_Reducida
		    	(@p1/@p2).should eq(Fraccion.new(1,1))
		end
		it "Operacion de multiplicacion" do
		    	@p1.fraccion_Reducida
		    	@p2.fraccion_Reducida
		    	(@p1*@p2).should eq(Fraccion.new(1,4))
		end
		it "Operacion de obtener resto" do
		   	@p1.fraccion_Reducida
		    	@p2.fraccion_Reducida
		    	(@p1%@p2).should eq(0)
		end
    end
end
