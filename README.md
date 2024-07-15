# Flutter_aula15_1

# código API:

  <?php
    $dado = rand(1,6);

    $vetor = array('dado' => "$dado");

    $json = json_encode($vetor);
    echo $json;
  ?>
