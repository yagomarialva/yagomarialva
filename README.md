class Student {
  constructor() {
    this.name = "Yago Marialva Bentes";
    this.role = "Full-Stack developer";
    this.location = "https://goo.gl/maps/j62SAvvmu78kCKZP6";
    this.knowledge_base = [
      "HTML",
      "CSS",
      "Java",
      "Javascript",
      "Typerscript"
    ];
    this.knowledge_base.unshift("Angular");
  }

  say_hi() {
    console.log(`Oi, obrigado pela visita!\n\nMeu nome é ${this.name}, sou de ${this.location}. no momento sou ${this.role} e atualmente estou focando ${this.knowledge_base[0]} para melhorar minhas habilidades.\n\ngosto de estudar várias coisas mas o que mais me especializei foi ${this.knowledge_base.slice(1).join(", ")}.`);
  }
}

const me = new Student();
me.say_hi();
