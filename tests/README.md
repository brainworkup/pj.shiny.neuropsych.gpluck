Tests and Coverage
================
08 February, 2023 14:15:38

- [Coverage](#coverage)
- [Unit Tests](#unit-tests)

This output is created by
[covrpage](https://github.com/yonicd/covrpage).

## Coverage

Coverage summary is created using the
[covr](https://github.com/r-lib/covr) package.

| Object                                                | Coverage (%) |
|:------------------------------------------------------|:------------:|
| pj.shiny.neuropsych.gpluck                            |    78.68     |
| [R/mod_name_of_module1.R](../R/mod_name_of_module1.R) |     0.00     |
| [R/mod_name_of_module2.R](../R/mod_name_of_module2.R) |     0.00     |
| [R/run_app.R](../R/run_app.R)                         |     0.00     |
| [R/golem_utils_server.R](../R/golem_utils_server.R)   |    77.78     |
| [R/golem_utils_ui.R](../R/golem_utils_ui.R)           |    87.94     |
| [R/app_config.R](../R/app_config.R)                   |    100.00    |
| [R/app_ui.R](../R/app_ui.R)                           |    100.00    |

<br>

## Unit Tests

Unit Test summary is created using the
[testthat](https://github.com/r-lib/testthat) package.

| file                                                            |   n |  time | error | failed | skipped | warning | icon |
|:----------------------------------------------------------------|----:|------:|------:|-------:|--------:|--------:|:-----|
| [test-app.R](testthat/test-app.R)                               |   1 | 0.037 |     0 |      0 |       0 |       0 |      |
| [test-fct_helpers.R](testthat/test-fct_helpers.R)               |   1 | 0.005 |     0 |      0 |       0 |       0 |      |
| [test-golem_utils_server.R](testthat/test-golem_utils_server.R) |  13 | 0.048 |     0 |      0 |       0 |       0 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R)         |  51 | 0.166 |     0 |      0 |       0 |       0 |      |
| [test-golem-recommended.R](testthat/test-golem-recommended.R)   |  10 | 0.193 |     0 |      0 |       1 |       0 | 🔶   |
| [test-utils_helpers.R](testthat/test-utils_helpers.R)           |   1 | 0.005 |     0 |      0 |       0 |       0 |      |

<details open>
<summary>
Show Detailed Test Results
</summary>

| file                                                                    | context            | test                           | status  |   n |  time | icon |
|:------------------------------------------------------------------------|:-------------------|:-------------------------------|:--------|----:|------:|:-----|
| [test-app.R](testthat/test-app.R#L2)                                    | app                | multiplication works           | PASS    |   1 | 0.037 |      |
| [test-fct_helpers.R](testthat/test-fct_helpers.R#L2)                    | fct_helpers        | multiplication works           | PASS    |   1 | 0.005 |      |
| [test-golem_utils_server.R](testthat/test-golem_utils_server.R#L2)      | golem_utils_server | not_in works                   | PASS    |   2 | 0.009 |      |
| [test-golem_utils_server.R](testthat/test-golem_utils_server.R#L7)      | golem_utils_server | not_null works                 | PASS    |   2 | 0.006 |      |
| [test-golem_utils_server.R](testthat/test-golem_utils_server.R#L12)     | golem_utils_server | not_na works                   | PASS    |   2 | 0.008 |      |
| [test-golem_utils_server.R](testthat/test-golem_utils_server.R#L17_L22) | golem_utils_server | drop_nulls works               | PASS    |   1 | 0.004 |      |
| [test-golem_utils_server.R](testthat/test-golem_utils_server.R#L26_L29) | golem_utils_server | %\|\|% works                   | PASS    |   2 | 0.007 |      |
| [test-golem_utils_server.R](testthat/test-golem_utils_server.R#L37_L40) | golem_utils_server | %\|NA\|% works                 | PASS    |   2 | 0.007 |      |
| [test-golem_utils_server.R](testthat/test-golem_utils_server.R#L48_L50) | golem_utils_server | rv and rvtl work               | PASS    |   2 | 0.007 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R#L2)              | golem_utils_ui     | Test with_red_star works       | PASS    |   2 | 0.008 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R#L10)             | golem_utils_ui     | Test list_to_li works          | PASS    |   3 | 0.010 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R#L22_L28)         | golem_utils_ui     | Test list_to_p works           | PASS    |   3 | 0.010 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R#L53)             | golem_utils_ui     | Test named_to_li works         | PASS    |   3 | 0.020 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R#L66)             | golem_utils_ui     | Test tagRemoveAttributes works | PASS    |   4 | 0.012 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R#L82)             | golem_utils_ui     | Test undisplay works           | PASS    |   8 | 0.041 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R#L110)            | golem_utils_ui     | Test display works             | PASS    |   4 | 0.009 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R#L124)            | golem_utils_ui     | Test jq_hide works             | PASS    |   2 | 0.005 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R#L132)            | golem_utils_ui     | Test rep_br works              | PASS    |   2 | 0.004 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R#L140)            | golem_utils_ui     | Test enurl works               | PASS    |   2 | 0.005 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R#L148)            | golem_utils_ui     | Test columns wrappers works    | PASS    |  16 | 0.037 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R#L172)            | golem_utils_ui     | Test make_action_button works  | PASS    |   2 | 0.005 |      |
| [test-golem-recommended.R](testthat/test-golem-recommended.R#L3)        | golem-recommended  | app ui                         | PASS    |   2 | 0.100 |      |
| [test-golem-recommended.R](testthat/test-golem-recommended.R#L13)       | golem-recommended  | app server                     | PASS    |   4 | 0.071 |      |
| [test-golem-recommended.R](testthat/test-golem-recommended.R#L24_L26)   | golem-recommended  | app_sys works                  | PASS    |   1 | 0.007 |      |
| [test-golem-recommended.R](testthat/test-golem-recommended.R#L36_L42)   | golem-recommended  | golem-config works             | PASS    |   2 | 0.012 |      |
| [test-golem-recommended.R](testthat/test-golem-recommended.R#L72)       | golem-recommended  | app launches                   | SKIPPED |   1 | 0.003 | 🔶   |
| [test-utils_helpers.R](testthat/test-utils_helpers.R#L2)                | utils_helpers      | multiplication works           | PASS    |   1 | 0.005 |      |

| Failed | Warning | Skipped |
|:-------|:--------|:--------|
| 🛑     | ⚠️      | 🔶      |

</details>
<details>
<summary>
Session Info
</summary>

| Field    | Value                                       |
|:---------|:--------------------------------------------|
| Version  | R version 4.2.2 Patched (2023-01-31 r83741) |
| Platform | x86_64-apple-darwin17.0 (64-bit)            |
| Running  | macOS Ventura 13.1                          |
| Language | en_US                                       |
| Timezone | America/Los_Angeles                         |

| Package  | Version    |
|:---------|:-----------|
| testthat | 3.1.6.9000 |
| covr     | 3.6.1      |
| covrpage | 0.1        |

</details>
<!--- Final Status : skipped/warning --->
