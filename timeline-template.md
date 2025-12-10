
        BODY_MESSAGE: "A branch do arquivo ${{ inputs.report_file }} é ${{ steps.branch_convention.outputs.report_branch }} e o commit referente a inclusão deste arquivo é ${{steps.commit_report.outputs.commit_sha}}"
