# Asctuce

nelmio_api_doc:
    sandbox:
        authentication:
            name: Authorization
            delivery: header          # `query`, `http`, and `header` are supported
            type:     bearer         # `basic`, `bearer` are supported
        entity_to_choice: false     # default is `true`, if `false`, entity collection
                                    # will not be mapped as choice



--------------------------------------------------------------------------------------
https://www.goetas.com/blog/how-to-add-custom-error-codes-to-your-symfony-api-responses/
