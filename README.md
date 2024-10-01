# cmcio-argocd

Este proyecto contiene manifestos de Kubernetes para la implementación y gestión de aplicaciones utilizando Argo CD.

## Requisitos

- Kubernetes 1.18+
- Argo CD 1.8+

## Instalación

1. Clona este repositorio:
    ```sh
    git clone https://github.com/tu-usuario/cmcio-argocd.git
    cd cmcio-argocd
    ```

2. Aplica los manifestos de Kubernetes:
    ```sh
    kubectl apply -f ./manifests/
    ```

## Uso

1. Accede a la interfaz de Argo CD:
    ```sh
    kubectl port-forward svc/argocd-server -n argocd 8080:443
    ```

2. Abre tu navegador y ve a `https://localhost:8080`.

3. Inicia sesión con las credenciales predeterminadas de Argo CD.

## Estructura del Proyecto

- `manifests/`: Contiene todos los archivos YAML necesarios para desplegar las aplicaciones en Kubernetes usando Argo CD.

## Contribuciones

¡Las contribuciones son bienvenidas! Por favor, abre un issue o un pull request para discutir cualquier cambio.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.