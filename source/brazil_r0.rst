**05/May** -- COVID-19 Time varying reproduction numbers estimation for Brazil
*****************************************************************************************************
These plots show the estimation of the instantaneous reproduction number for all
the states in Brazil. These reports uses the method described in the work 
`A New Framework and Software to Estimate Time-Varying Reproduction Numbers During Epidemics <https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3816335/>`_. We used the serial interval parameters similar to the ones used
by `CMMID <https://cmmid.github.io/topics/covid19/>`_ with a :math:`\mu = 4.7 (3.7 - 6.0)`
and :math:`\sigma = 2.9 (1.9 - 4.9)` with a log-normal distribution.

.. note:: This plot uses official data from government, reports until
          05/May. This method is sensitive to changes in COVID-19
          testing procedures and the level of effort used to detect cases.
          Therefore, changes in the testing efforts will introduce bias
          if the testing practices are not kept consistent. So please
          keep in mind these limitations, that are often not stated in
          many analysis around there.

Summary for the last instantaneous reproduction number estimate
===============================================================================
.. rubric:: Map for the accumulated cases

.. raw:: html

    <iframe src="_static/restim_cases_map.html" height="591px" width="100%" frameBorder="0"></iframe>

.. rubric:: Map for the last instantaneous reproduction number estimate

.. raw:: html

    <iframe src="_static/restim_map.html" height="591px" width="100%" frameBorder="0"></iframe>

.. rubric:: Map of states with mean reproduction number R(t) > 1.0

.. raw:: html

    <iframe src="_static/restim_badr_map.html" height="591px" width="100%" frameBorder="0"></iframe>

.. rubric:: Map for the accumulated deaths by COVID-19

.. raw:: html

    <iframe src="_static/restim_deaths_map.html" height="591px" width="100%" frameBorder="0"></iframe>

.. rubric:: Summary for the last instantaneous reproduction number estimate

Last update: **05/May**

.. image:: _static/br/r0_estim/estim_all.svg
    :width: 700

.. rubric:: Summary table for the last instantaneous reproduction number estimate

.. raw:: html
    
    <style>
        table.greyGridTable {
          border: 2px solid #FFFFFF;
          width: 100%;
          text-align: center;
          border-collapse: collapse;
        }
        table.greyGridTable td, table.greyGridTable th {
          border: 1px solid #FFFFFF;
          padding: 3px 4px;
        }
        table.greyGridTable tbody td {
          font-size: 13px;
        }
        table.greyGridTable td:nth-child(even) {
          background: #EBEBEB;
        }
        table.greyGridTable thead {
          background: #FFFFFF;
          border-bottom: 4px solid #333333;
        }
        table.greyGridTable thead th {
          font-size: 15px;
          font-weight: bold;
          color: #333333;
          text-align: center;
          border-left: 2px solid #333333;
        }
        table.greyGridTable thead th:first-child {
          border-left: none;
        }

        table.greyGridTable tfoot {
          font-size: 14px;
          font-weight: bold;
          color: #333333;
          border-top: 4px solid #333333;
        }
        table.greyGridTable tfoot td {
          font-size: 14px;
        }
    </style>

    <table class="greyGridTable">
    <thead>
    <tr>
    <th>State</th>
    <th>Mean Estimated R (CI 0.975)</th>
    </tr>
    </thead>
    <tbody>
    
    <tr>
        <td>AC</td>
        <td>2.12 (1.61 - 2.83)</td>
    </tr>
    
    <tr>
        <td>TO</td>
        <td>2.01 (1.50 - 2.72)</td>
    </tr>
    
    <tr>
        <td>AP</td>
        <td>1.89 (1.58 - 2.17)</td>
    </tr>
    
    <tr>
        <td>SE</td>
        <td>1.77 (1.40 - 2.29)</td>
    </tr>
    
    <tr>
        <td>RR</td>
        <td>1.68 (1.40 - 2.03)</td>
    </tr>
    
    <tr>
        <td>RO</td>
        <td>1.61 (1.40 - 1.84)</td>
    </tr>
    
    <tr>
        <td>AM</td>
        <td>1.58 (1.43 - 1.72)</td>
    </tr>
    
    <tr>
        <td>MG</td>
        <td>1.55 (1.35 - 1.74)</td>
    </tr>
    
    <tr>
        <td>CE</td>
        <td>1.53 (1.42 - 1.60)</td>
    </tr>
    
    <tr>
        <td>PI</td>
        <td>1.50 (1.29 - 1.75)</td>
    </tr>
    
    <tr>
        <td>PB</td>
        <td>1.48 (1.27 - 1.72)</td>
    </tr>
    
    <tr>
        <td>RN</td>
        <td>1.44 (1.27 - 1.65)</td>
    </tr>
    
    <tr>
        <td>ES</td>
        <td>1.39 (1.23 - 1.60)</td>
    </tr>
    
    <tr>
        <td>PA</td>
        <td>1.38 (1.25 - 1.53)</td>
    </tr>
    
    <tr>
        <td>DF</td>
        <td>1.36 (1.16 - 1.60)</td>
    </tr>
    
    <tr>
        <td>MA</td>
        <td>1.35 (1.23 - 1.50)</td>
    </tr>
    
    <tr>
        <td>BA</td>
        <td>1.34 (1.23 - 1.45)</td>
    </tr>
    
    <tr>
        <td>SC</td>
        <td>1.32 (1.15 - 1.53)</td>
    </tr>
    
    <tr>
        <td>MT</td>
        <td>1.27 (1.04 - 1.52)</td>
    </tr>
    
    <tr>
        <td>RS</td>
        <td>1.19 (1.07 - 1.32)</td>
    </tr>
    
    <tr>
        <td>AL</td>
        <td>1.15 (1.02 - 1.29)</td>
    </tr>
    
    <tr>
        <td>RJ</td>
        <td>1.13 (1.06 - 1.20)</td>
    </tr>
    
    <tr>
        <td>PE</td>
        <td>1.12 (1.05 - 1.20)</td>
    </tr>
    
    <tr>
        <td>PR</td>
        <td>1.02 (0.89 - 1.17)</td>
    </tr>
    
    <tr>
        <td>SP</td>
        <td>0.97 (0.91 - 1.03)</td>
    </tr>
    
    <tr>
        <td>GO</td>
        <td>0.96 (0.83 - 1.10)</td>
    </tr>
    
    <tr>
        <td>MS</td>
        <td>0.82 (0.58 - 1.11)</td>
    </tr>
    
    </tbody>
    </table>


**State**: Acre / AC
===============================================================================

.. image:: _static/br/r0_estim/state_ac.png
  :width: 700


**State**: Alagoas / AL
===============================================================================

.. image:: _static/br/r0_estim/state_al.png
  :width: 700


**State**: Amazonas / AM
===============================================================================

.. image:: _static/br/r0_estim/state_am.png
  :width: 700


**State**: Amapá / AP
===============================================================================

.. image:: _static/br/r0_estim/state_ap.png
  :width: 700


**State**: Bahia / BA
===============================================================================

.. image:: _static/br/r0_estim/state_ba.png
  :width: 700


**State**: Ceará / CE
===============================================================================

.. image:: _static/br/r0_estim/state_ce.png
  :width: 700


**State**: Distrito Federal / DF
===============================================================================

.. image:: _static/br/r0_estim/state_df.png
  :width: 700


**State**: Espírito Santo / ES
===============================================================================

.. image:: _static/br/r0_estim/state_es.png
  :width: 700


**State**: Goiás / GO
===============================================================================

.. image:: _static/br/r0_estim/state_go.png
  :width: 700


**State**: Maranhão / MA
===============================================================================

.. image:: _static/br/r0_estim/state_ma.png
  :width: 700


**State**: Minas Gerais / MG
===============================================================================

.. image:: _static/br/r0_estim/state_mg.png
  :width: 700


**State**: Mato Grosso do Sul / MS
===============================================================================

.. image:: _static/br/r0_estim/state_ms.png
  :width: 700


**State**: Mato Grosso / MT
===============================================================================

.. image:: _static/br/r0_estim/state_mt.png
  :width: 700


**State**: Pará / PA
===============================================================================

.. image:: _static/br/r0_estim/state_pa.png
  :width: 700


**State**: Paraíba / PB
===============================================================================

.. image:: _static/br/r0_estim/state_pb.png
  :width: 700


**State**: Pernambuco / PE
===============================================================================

.. image:: _static/br/r0_estim/state_pe.png
  :width: 700


**State**: Piauí / PI
===============================================================================

.. image:: _static/br/r0_estim/state_pi.png
  :width: 700


**State**: Paraná / PR
===============================================================================

.. image:: _static/br/r0_estim/state_pr.png
  :width: 700


**State**: Rio de Janeiro / RJ
===============================================================================

.. image:: _static/br/r0_estim/state_rj.png
  :width: 700


**State**: Rio Grande do Norte / RN
===============================================================================

.. image:: _static/br/r0_estim/state_rn.png
  :width: 700


**State**: Rondônia / RO
===============================================================================

.. image:: _static/br/r0_estim/state_ro.png
  :width: 700


**State**: Roraima / RR
===============================================================================

.. image:: _static/br/r0_estim/state_rr.png
  :width: 700


**State**: Rio Grande do Sul / RS
===============================================================================

.. image:: _static/br/r0_estim/state_rs.png
  :width: 700


**State**: Santa Catarina / SC
===============================================================================

.. image:: _static/br/r0_estim/state_sc.png
  :width: 700


**State**: Sergipe / SE
===============================================================================

.. image:: _static/br/r0_estim/state_se.png
  :width: 700


**State**: São Paulo / SP
===============================================================================

.. image:: _static/br/r0_estim/state_sp.png
  :width: 700


**State**: Tocantins / TO
===============================================================================

.. image:: _static/br/r0_estim/state_to.png
  :width: 700

