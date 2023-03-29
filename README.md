<h2>Código para criar o Banco de Dados e a Table</h2>
<hr>
<code>CREATE SCHEMA `novasraizes` ;
CREATE TABLE `novasraizes`.`admin` (
  `login` VARCHAR(45) NOT NULL,
  `senha` VARCHAR(45) NOT NULL,
  `idAdmin` INT NOT NULL AUTO_INCREMENT,
  UNIQUE INDEX `idAdmin_UNIQUE` (`idAdmin` ASC),
  UNIQUE INDEX `senha_UNIQUE` (`senha` ASC),
  UNIQUE INDEX `login_UNIQUE` (`login` ASC));

INSERT INTO `novasraizes`.`admin` (`login`, `senha`) VALUES ('AdminPts', 'Pts1903');
INSERT INTO `novasraizes`.`admin` (`login`, `senha`) VALUES ('AdminMdrs', 'Mdrs3012');
INSERT INTO `novasraizes`.`admin` (`login`, `senha`) VALUES ('AdminPrs', 'Prs3105');
</code>
<hr>
