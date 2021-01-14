class Chelovek:
    imja = "Maksim"
    
    def pokazatj_info(self):
        print("Privet, menja zovut", self.imja)

chelovek1 = Chelovek()
chelovek1.pokazatj_info()

chelovek2 = Chelovek()
chelovek2.imja = "Tanja"
chelovek2.pokazatj_info()