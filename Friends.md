class Sercheetos{
    constructor(nome){
        this.nome = nome
    }


 study(){
    console.log(this.nome + " studyng!")
}





playing(){
    console.log(this.nome + " studying!")
}

}



class Najon extends Sercheetos{
    constructor(nome){
        super(nome)

    }
         coding(){
            console.log(this.nome + " coding ")
        }
    
}


const sercheetos = new Sercheetos("Sercheetos")
const najon = new Najon("Najon")


najon.coding()
