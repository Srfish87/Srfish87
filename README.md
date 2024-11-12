function calcularNovoSalario() {
  const salario = parseFloat(prompt("Digite o salário atual:"));
  const novoSalario = salario * 1.5;
  alert(`O novo salário com aumento de 50% é: R$ ${novoSalario.toFixed(2)}`);
}
